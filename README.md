# HR Skill Pack

Open-source AI skills for HR and L&D teams. Each skill is a plain-English instruction set you paste into [Manus](https://manus.im) or any agentic AI. Upload your data, the agent runs the workflow end-to-end. No code required.

Built by [Chee Ann](https://cheeann.com). MIT licensed.

Originally developed for Vspire Academy's HR community session, April 2026. Published publicly so any HR or L&D team can use, fork, or modify it.

## Skills in this pack

| Skill | What it does | Status |
|---|---|---|
| [Post-Training Report](./post-training-report) | Generate Kirkpatrick-aligned HTML evaluation reports from survey and collaboration board data | Ready |
| Job Post Designer | Generate employer-branding images for targeted audiences (early-career vs senior) | Coming soon |
| JD Writer | Draft job descriptions with bias-language audit | Coming soon |
| CV Screen | Rank a folder of CVs against a JD with reasoning and audit trail | Coming soon |
| Offer Letter Generator | Five role variants (full-time, contract, intern, senior, expat) | Coming soon |

## Install on Manus (2 min)

1. Start a new session at [manus.im](https://manus.im)
2. Open the skill folder in this repo, e.g. `post-training-report/`
3. Copy the contents of `SKILL.md`
4. Paste it into Manus as your first message
5. Upload your input files (see the skill's `inputs-checklist.md`)
6. Type: *"Run the skill on the files I uploaded."*

The agent reads the instructions and executes.

## Works beyond Manus

These skills are plain-English instruction sets. They run on Claude, ChatGPT with file tools, Gemini with code execution, or any agentic AI that can read files and generate output. Nothing is platform-specific.

## Design principle

Each skill is grounded in established methodology rather than opinion. The post-training report skill references Kirkpatrick's four levels of evaluation, Knowles's andragogy, Kolb's experiential learning cycle, Bandura's social learning theory, and Bloom's taxonomy. L&D leadership reading the output should recognise the framework, not just the output.

Treating the AI as a disciplined executor of known evaluation methodology produces work that reads as professional documentation, not marketing collateral.

## Contributing

PRs welcome. Each skill folder contains:

- `SKILL.md`: the instructions the agent follows
- `template.html` or `template.md`: output template with `{{placeholders}}`
- `inputs-checklist.md`: what the user prepares before running
- `sample-inputs/`: a working example for testing
- `example-output.html`: what the finished output looks like

Keep skills under 200 lines of instructions. If a skill needs more, it probably needs to be two skills.

## License

MIT. Use it, fork it, modify it, ship it. Commercial use permitted.

## Acknowledgements

Created for Vspire Academy's HR community session (24 April 2026) at TRX Kuala Lumpur. Thanks to the HR practitioners in the room who tested the workflow live and validated the design.
