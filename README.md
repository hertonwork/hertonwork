<h1 align="center">Herton Fontineli</h1>

<p align="center">
  <b>CTO · AI Platform Engineer · Software Architect</b><br>
  I lead small teams that rebuild platforms, ship AI systems to production and keep them up under real load.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/herton">LinkedIn</a> ·
  <a href="https://github.com/LabskAI">@LabskAI</a>
</p>

---

### Now

- **CTO, [Aftermarket.com](https://aftermarket.com)**. I lead **[Falcon](https://falcon.how)**, an AI agent studio in private pilot, and rebuilt the domain archecture on AWS/Cloudflare in a few months: 50K parked domains serving 1.5M pages, up through several DDoS attacks.
- **Founder, [Labs Kai](https://labskai.com)**. AI products and small, fast open source.

Before that: Chief Architect & Development Manager at ACCESS Newswire (led 6 engineers through a post-acquisition PHP/C# integration, built a reverse-lookup + RAG classifier that tagged millions of media records to IPTC Media Topics with no LLM call per item), and Senior Software Engineer at Ziff Media Group, on the enterprise Laravel CMS behind AskMen and Mashable.

### Products

| | |
| --- | --- |
| **[Falcon](https://falcon.how)** | AI agent studio at Aftermarket.com (private pilot). Laravel integration: [falcon-skills-laravel](https://github.com/lead-com-dev/falcon-skills-laravel) |
| **[Taxonomy Engine](https://api.labskai.dev)** | REST + MCP classifier to IPTC Media Topics in 4 languages: pgvector search, fine-tuned small-model reranker, confidence scores, editor routing, eval harness |

### Open source

- **[server](https://github.com/hertonwork/server)**: a static server for single-page apps in one Node file. No npm dependencies, 100/100 Lighthouse, self-updating PWA, MCP endpoint for coding agents. `npx @labs_kai/server` · live at [server.herton.work](https://server.herton.work).
- **[minim](https://github.com/hertonwork/minim)**: the smallest HTML-first reactive library (0.5 KB core, 1.2 KB paste-in). Live at [minim.herton.work](https://minim.herton.work).
- **[sscss](https://github.com/hertonwork/sscss)**: super small CSS. 1–3 letter utilities, and a generator that ships only the rules your page uses. Live at [sscss.herton.work](https://sscss.herton.work).
- **[shopmade-core](https://github.com/LabskAI/shopmade-core)**: Laravel website and customer system for one business, editable from Claude over MCP.

### Agent skills

Each one teaches a coding agent to do what the project does for its own pages. Install with `npx skills add <repo>`.

- **[minim-page](https://github.com/hertonwork/minim/tree/main/skills/minim-page)** (`hertonwork/minim`): one-file pages that score 100/100/100/100, with Minim for state, sscss for styles and a preflight checker.
- **[shader-hero](https://github.com/hertonwork/minim/tree/main/skills/shader-hero)** (`hertonwork/minim`): a living hero background (an ocean, drifting ink, lanes of traffic) that keeps the 100. Runs on real GPUs only.
- **[sscss](https://github.com/hertonwork/sscss/tree/main/skills/sscss)** (`hertonwork/sscss`): style a page with sscss and inline only the CSS it uses.
- **[simple-server](https://github.com/hertonwork/server/tree/main/skills/simple-server)** (`hertonwork/server`): serve a single-page app, ship it as a PWA, and let agents inspect it over MCP.
- **[basecode-skills](https://github.com/hertonwork/basecode-skills)**: make coding agents write readable code and idiomatic Laravel.

### Stack

AI agents · Tool use · RAG · Evals · Embeddings · Reranking · MCP<br>
AWS · Docker · Kubernetes · nginx · Linux<br>
PHP · Laravel · Python · TypeScript · Node.js · C# · Vue.js<br>
PostgreSQL · pgvector · MySQL
