# HR Skill Pack

Free, open-source AI skills for HR teams. Copy any skill into [Manus](https://manus.im), upload your files, and the agent runs it end-to-end.

Built by [Chee Ann](https://cheeann.com). MIT licensed. Steal freely.

## Skills in this pack

| Skill | What it does | Status |
|---|---|---|
| [Post-Training Report](./post-training-report) | Turn survey results + Padlet/collaboration boards into a stunning HTML post-training report | ✅ Ready |
| Job Post Designer | Generate employer-branding images for Gen Z vs senior hires | 🟡 Coming |
| JD Writer | Write job descriptions with bias-language audit | 🟡 Coming |
| CV Screen | Rank a folder of CVs against a JD with reasoning | 🟡 Coming |
| Offer Letter Generator | 5 variants (full-time, contract, intern, senior, expat) | 🟡 Coming |

## How to install a skill on Manus (2 min)

1. Go to [manus.im](https://manus.im) and start a new session
2. Open the skill folder in this repo (e.g. `post-training-report/`)
3. Copy the contents of `SKILL.md`
4. In Manus, paste it into the chat as your first message
5. Upload your input files (see each skill's `inputs-checklist.md`)
6. Type: *"Run the skill on the files I uploaded."*

The agent does the rest.

## What if I don't use Manus?

These skills also work on Claude, ChatGPT with tools, or any agentic AI that can read files and produce output. The instructions are plain English, not platform-specific.

## Why this exists

HR teams are sitting on hours of manual post-training, recruitment, and policy work that AI can automate tonight — for free. The bottleneck isn't the tech. It's knowing the recipe.

This pack is the recipe.

## Contributing

PRs welcome. Each skill lives in its own folder with:
- `SKILL.md` — the instructions the agent follows
- `template.html` or `template.md` — output template with `{{placeholders}}`
- `inputs-checklist.md` — what the user prepares before running
- `sample-inputs/` — a working example so anyone can test in 2 min
- `example-output.html` — what the finished output looks like

## License

MIT. Use it. Fork it. Sell it. Just don't blame me if your HR dashboard suddenly looks better than your CEO's.
