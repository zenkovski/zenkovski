### Hi, I'm Lukáš 👋

I build **AI systems that can be measured**: retrieval (RAG), tools for AI agents (MCP), and evaluation that tells me when something breaks.
Based in Czechia · open to remote work.

**What I focus on**
- Retrieval pipelines with citations, and an honest "I don't know" when the source is silent
- Exposing knowledge to AI agents via **MCP** and REST APIs
- Offline evaluation: held-out test sets, confidence intervals, quality gates in CI
- Test automation with Playwright, including black-box tests of AI apps

**Featured projects**

| Project | What it is | Live | CI |
|---|---|---|---|
| [kontrola-faktur](https://github.com/zenkovski/kontrola-faktur) | Invoice checks where AI reads and code decides. Web, REST API, MCP. Eval: 40 / 40 decisions, 0 false approvals; 123 tests | [demo](https://kontrola-faktur.web-ukazka.pages.dev) | [![tests](https://github.com/zenkovski/kontrola-faktur/actions/workflows/tests.yml/badge.svg)](https://github.com/zenkovski/kontrola-faktur/actions/workflows/tests.yml) |
| [rag-demo](https://github.com/zenkovski/rag-demo) | Cited-answer RAG over 4 Czech labour laws. Hybrid retrieval, FastAPI, MCP. 108 / 112 correct answers on 134 held-out questions | [lukas-rag.vercel.app](https://lukas-rag.vercel.app) | [![tests](https://github.com/zenkovski/rag-demo/actions/workflows/tests.yml/badge.svg)](https://github.com/zenkovski/rag-demo/actions/workflows/tests.yml) |
| [qa-portfolio](https://github.com/zenkovski/qa-portfolio) | Playwright + TypeScript: UI, API, a11y, security, black-box tests of my RAG app. 117 cases in 4 browsers, 22 bug reports | [lukas-qa.vercel.app](https://lukas-qa.vercel.app) | [![tests](https://github.com/zenkovski/qa-portfolio/actions/workflows/tests.yml/badge.svg)](https://github.com/zenkovski/qa-portfolio/actions/workflows/tests.yml) |

**Status**
- **kontrola-faktur:** actively developed (October 2026).
- **rag-demo:** maintained. Changes come from measurements; open failures are listed in its [failure gallery](https://github.com/zenkovski/rag-demo/blob/main/docs/failure-gallery.md).
- **qa-portfolio:** a finished snapshot. CI still runs every Monday against the live sites, so a change on a target shows up. On 19. 10. 2026 it caught a bug that had been fixed ([incident](https://github.com/zenkovski/qa-portfolio/blob/main/docs/incidents/2026-10-19-bug-rag-01-opraveny.md)).

**Stack:** Python · FastAPI · TypeScript · Playwright · MCP · embeddings & BM25 · Docker · GitHub Actions · Vercel · Cloudflare Pages

**How I work:** I build with AI coding agents (Claude Code). The AI writes and explores; I decide the design, measure the result and own what ships.

📫 [LinkedIn](https://www.linkedin.com/in/luk%C3%A1%C5%A1-proch%C3%A1zka-635799228/) · ahoj@zennstudio.cz
