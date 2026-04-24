# Output Schema: OA Form Scanner

## Filename

`{client-slug}-oa-responses-{YYYY-MM-DD}.csv`

## Columns (in this order, no exceptions)

| Column | Type | Description |
|---|---|---|
| `participant_id` | string | Assigned sequentially: P001, P002, P003... |
| `name` | string | Verbatim from form header. `UNREADABLE` if illegible. |
| `department` | string | Verbatim from form header. `UNKNOWN` if blank. |
| `Q1_content_relevant` | int 1-5 or NA | Content relevance rating |
| `Q2_content_clear` | int 1-5 or NA | Content clarity rating |
| `Q3_content_practical` | int 1-5 or NA | Practical application rating |
| `Q4_content_duration` | int 1-5 or NA | Duration appropriateness rating |
| `Q5_content_materials` | int 1-5 or NA | Materials quality rating |
| `Q6_provider_organised` | int 1-5 or NA | Provider organisation rating |
| `Q7_provider_communication` | int 1-5 or NA | Provider communication rating |
| `Q8_provider_venue` | int 1-5 or NA | Venue rating |
| `Q9_provider_support` | int 1-5 or NA | Provider support rating |
| `Q10_provider_value` | int 1-5 or NA | Provider value rating |
| `Q11_trainer_knowledge` | int 1-5 or NA | Trainer knowledge rating |
| `Q12_trainer_delivery` | int 1-5 or NA | Trainer delivery rating |
| `Q13_trainer_engagement` | int 1-5 or NA | Trainer engagement rating |
| `Q14_trainer_responsiveness` | int 1-5 or NA | Trainer responsiveness rating |
| `Q15_trainer_overall` | int 1-5 or NA | Overall trainer rating |
| `open_comment` | string | Verbatim open feedback. Empty if blank. |
| `confidence_flag` | enum | `OK`, `REVIEW_RATINGS`, `REVIEW_IDENTITY`, `REVIEW_COMMENT`, `UNREADABLE` |

## Why this schema

The schema is identical to the survey-results input expected by the Post-Training Report skill. The two skills chain with zero reformatting.

## If the form is non-standard

If the input uses a different scale, number of criteria, or section structure, the skill adapts the schema and announces the variant in its summary. In that case, the output filename becomes `{client-slug}-oa-responses-{YYYY-MM-DD}-variant.csv` and the column count will differ.

Standard output (15 questions, 1 to 5 scale) remains the default and is compatible with the Post-Training Report skill out of the box.
