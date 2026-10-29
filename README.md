# Timo Tautenhahn

**Field CTO · Data, Analytics & AI at Salesforce**

Nearly two decades between customers and engineers. Now I build the AI systems myself, and measure them.

I design and build AI and data systems, and the evaluation harnesses that show whether any of it is ready for production: text-to-SQL, multimodal pipelines, and software that works offline. I write the code, and I can explain the trade-offs to the people who sign off on it.

## Point of view

Customers choose the model and control their data. Agents prove their value in evals and measured outcomes, not in demos.

## What I work on

- **Evals before claims.** Execution-based scoring instead of string matching. A query is right if it returns the right rows, not if it looks like the gold SQL.
- **Grounding on the live schema.** Text-to-SQL that is given the real schema and example values, and judged by what it returns.
- **Multimodal pipelines.** Crawl, tag with a vision model, and search a library by what the images show, with the tagger measured against a labelled set.
- **Software people can rely on.** An offline, private speech board for people who cannot currently speak: on-device, no account, no network.

## Selected work

| Project | What it shows | Evidence |
|---|---|---|
| [grounded-text-to-sql-lab](https://github.com/TimoTautenhahn/grounded-text-to-sql-lab) | Execution-match eval for text-to-SQL, offline and reproducible | 13 gold questions. A naive baseline scores 38.5% and the harness self-test scores 100%, so the metric separates right from wrong |
| [ai-visual-asset-intelligence](https://github.com/TimoTautenhahn/ai-visual-asset-intelligence) | Crawl, vision-tag, search by content, with AI tagging optional | 24-panel labelled set for tag precision and coverage. Limits documented: tag-overlap similarity, no robots.txt handling |
| [accessible-voice-aac-assistant](https://github.com/TimoTautenhahn/accessible-voice-aac-assistant) | Installable offline speech board in German and English | On-device speech, n-gram next-word prediction, personal bigrams learned locally |
| [capture-time-deck-builder](https://github.com/TimoTautenhahn/capture-time-deck-builder) | Media folders to slide decks by capture time | Local OAuth broker |
| [applied-ai-architect-portfolio-site](https://github.com/TimoTautenhahn/applied-ai-architect-portfolio-site) | Portfolio CMS | Database-enforced visibility, link-gated previews |

## At work

- **Model choice stays with the customer.** Any model behind an LLM gateway: masking, keys, cost, rate limits, usage tracking.
- **Measured quality.** Golden-set evals on chart accuracy, factual grounding, calculation validity, and latency. A Python harness, built with AI coding agents, runs tiered customer question catalogs against an agentic analytics MCP server.
- **Governed grounding.** Semantic layers, knowledge graphs, ontologies, and RAG, with SME-validated Q&A calibration and regression tests.

## How I work

- Start from the decision the user has to make, not from the model.
- Measure before I claim. If there is no eval yet, the README says so.
- Say what is not done. Every project lists its limits and next steps.
- Prototype fast, then make it boring: configuration over hardcoding, no secrets in code, tests.

## Beyond the repos

- 150+ talks on four continents, including Dreamforce. AI keynotes at Salesforce World Tour Frankfurt 2025 and Tableau Innovation Day Dubai 2023.
- Developer blog: [tableaufans.com](https://tableaufans.com).
- Open source: Tableau integration and JavaScript frontend of the Wafer Extension Framework (Virtual Manufacturing Summit EMEA 2021).

## Background

Field CTO for Data, Analytics & AI at Salesforce since 2022. Before that at Tableau (2014 to 2022) and IBM (2008 to 2014), working with enterprises across DACH and EMEA. Current focus: agentic analytics, knowledge graphs, and answers users can verify. German (native), English (fluent).
