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
| 8 | [Line of Sight](08-line-of-sight.html) | Attention in depth: the math step by step, multi-head, and long-context costs |
| 9 | [Boot Camp](09-boot-camp.html) | Training a tiny model from scratch and fine-tuning an open model with LoRA |
| 10 | [Quarantine Protocol](10-quarantine-protocol.html) | Responsible vibe coding: building with AI without putting your team at risk |
| 11 | [Proving Grounds](11-proving-grounds.html) | Evaluating AI systems |
| 12 | [Breach Drill](12-breach-drill.html) | Prompt injection and LLM app security |
| 13 | [Trail Network](13-trail-network.html) | Knowledge graphs with LLMs |
| 14 | [Supply Lines](14-supply-lines.html) | Shipping and running LLM apps |
| 15 | [Council Briefing](15-council-briefing.html) | AI for leaders and managers |
| 16 | [Salvaged Records](16-salvaged-records.html) | Getting structured data out of PDFs, scans, forms and images |

## Course map

[`map.html`](map.html) shows how the courses connect: required and recommended prerequisites, and seven learning tracks (Leaders, Foundations, App builder, Citizen builder, Agent operator, Model internals, Data).

## Viewing

Open any `.html` file in a browser, or turn on GitHub Pages (Settings → Pages → deploy from `main`, root) to host them. `index.html` becomes the landing page.

## Adding your logo

Every page has a dashed "Your logo" placeholder in the header bar. Add your logo file to the repo, then replace the placeholder's text with an image, for example:

```html
<div class="logo" role="img" aria-label="Logo placeholder"><img src="logo.svg" alt="Your organization"></div>
```

The box is 132 × 44 px; the image scales to fit. You can remove the dashed border by deleting `border` from the `.logo` rule.
