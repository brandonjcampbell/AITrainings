# Survivor Field Manuals

Interactive AI and data trainings, themed around surviving a zombie apocalypse. Each course is one self-contained HTML page; open `index.html` for the course list.

| # | Course | Topic |
|---|---|---|
| 0 | [Field Autopsy](00-field-autopsy.html) | How large language models work, from tokens to training (start here) |
| 1 | [Survival Odds](01-survival-odds.html) | Prompt engineering as making the response you want the most probable result |
| 2 | [Outpost Protocols](02-outpost-protocols.html) | Structuring one-shot prompts into agentic solutions |
| 3 | [Lakehouse Supply Run](03-lakehouse-supply-run.html) | Databricks fundamentals, access tokens, and pulling data with Python |
| 4 | [Off-Grid Intelligence](04-off-grid-intelligence.html) | Prototyping a Python app with Ollama |
| 5 | [Squad Orders](05-squad-orders.html) | Getting the most out of coding agents like Claude Code and Devin |
| 6 | [Common Frequency](06-common-frequency.html) | The Model Context Protocol: building and connecting MCP servers in Python |
| 7 | [Archive Run](07-archive-run.html) | Retrieval-augmented generation over your own documents |

## Viewing

Open any `.html` file in a browser, or turn on GitHub Pages (Settings → Pages → deploy from `main`, root) to host them. `index.html` becomes the landing page.

## Adding your logo

Every page has a dashed "Your logo" placeholder in the header bar. Add your logo file to the repo, then replace the placeholder's text with an image, for example:

```html
<div class="logo" role="img" aria-label="Logo placeholder"><img src="logo.svg" alt="Your organization"></div>
```

The box is 132 × 44 px; the image scales to fit. You can remove the dashed border by deleting `border` from the `.logo` rule.
