# Timo Tautenhahn

**Applied AI architect and field CTO. Twenty years between customers and engineers. I still build, and I measure.**

I build AI and data systems, and the evals that show whether they are ready for production: text-to-SQL, multimodal pipelines, and software that works offline. I write the code, and I can explain the trade-offs to the people who sign off on it.

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

## How I work

- Start from the decision the user has to make, not from the model.
- Measure before I claim. If there is no eval yet, the README says so.
- Say what is not done. Every project lists its limits and next steps.
- Let users verify: show assumptions and sources, not just answers.
- Prototype fast, then make it boring: configuration over hardcoding, no secrets in code, tests.

## Where I'm useful

- **Customers and field teams:** turning "we want AI on our data" into a measurable eval, a governed data foundation, and a production plan.
- **Product and research:** bringing what strategic customers hit in production back as concrete requirements and failing test cases.
- **Executives:** translating technical trade-offs into decisions, risk, and return.

## Background

Two decades as solutions architect and field CTO for the world's largest enterprises across data, analytics, and AI. I work with strategic customers globally, stay ahead of where the industry is heading, and turn that into product strategy. Current focus: agentic analytics, knowledge graphs, and answers users can verify.
