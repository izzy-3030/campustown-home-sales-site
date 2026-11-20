# Agent log

Add a dated entry each time you work with your AI coding agent, with the newest entry at the bottom. Each entry records what you asked the agent, what it produced, and what you checked or changed. Paste your key prompts in exactly as you typed them. Include at least one time the agent got something wrong, and how you caught it.

Copy this outline for each entry:

```markdown
## YYYY-MM-DD: What you worked on

- **Asked:** "Paste your prompt here."
- **Agent produced:** What it made or changed.
- **Checked or changed:** How you checked it, and what you fixed.
```

## 2026-11-19: Show rounded city median prices

- **Asked:** "Read AGENTS.md and docs/data_description_sheet.md first. Then show every median sale price on index.html rounded to whole dollars, in both the chart and the table."
- **Agent produced:** Replaced the starter page with a chart and table generated from the CSV. Prices below $1,000 are excluded as described in the data sheet; displayed medians are rounded to whole dollars.
- **Checked or changed:** Read the project instructions and data description sheet before editing. The page fetches the repository CSV and computes each city/state median in the browser; open the page on the published site to see the chart and table.
