# Hi, I'm Abdu Alim 👋

**Computer Science @ Langara College** | Full-stack Software Engineer 

**Open to:** Software engineering internships & new-grad roles (full-stack, backend, AI-adjacent product engineering)

I own products **end-to-end** — UI, APIs, data models, auth, automated tests, CI, and production deploys.  

**3 live applications** on Vercel · **113+ automated tests** · CI on every change.

---

## Selected work

### [ReviewLens](https://review-lens-app.vercel.app/) — AI-powered review intelligence

**Turned unstructured customer feedback into actionable, shareable reports**, measured by a full production upload → analyze → export workflow with **51 passing unit tests** and GitHub Actions CI, by building a Next.js/TypeScript application with OpenAI-driven theme and sentiment analysis, Prisma/PostgreSQL persistence, PDF/CSV export, and password-protected share links.

| | |
|:--|:--|
| **Impact** | Product teams get themes, sentiment, and an executive summary without manual review triage |
| **Stack** | Next.js · TypeScript · Prisma · PostgreSQL · OpenAI · Vitest · GitHub Actions · Vercel |
| **Links** | [Website](https://review-lens-app.vercel.app/) · [Code](https://github.com/Arlikhozhaev/ReviewLens) |

---

### [AutoDev](https://autodev-one.vercel.app/) — autonomous codebase improvement agent

**Automated the improve-and-ship loop for Python repositories**, measured by a **5-phase async pipeline** (clone → analyze → LLM refactor → validate → GitHub PR) with **5 safety gates**, **4 static analysis tools**, and **35 pytest tests**, by engineering FastAPI + Celery workers on PostgreSQL/Redis, Claude-powered refactors with **3 retry attempts per issue**, and a Next.js operations dashboard deployed across **6 services** (Railway + Vercel).
| | |
|:--|:--|
| **Impact** | Paste a GitHub URL → static analysis and validated refactors → PR only if every safety gate passes |
| **Stack** | Python · FastAPI · Celery · Redis · PostgreSQL · Claude · Next.js · Docker · Railway · Vercel |
| **Links** | [Website](https://autodev-one.vercel.app/) · [API Docs](https://autodev-production.up.railway.app/docs) · [Code](https://github.com/Arlikhozhaev/autodev) |

---

### [ProfessorMatch&nbsp;AI](https://professor-match-ai.vercel.app/) — hybrid RAG professor discovery

**Improved search quality when exact keywords miss the intent**, measured by a **3-stage retrieval pipeline** (vector → semantic → keyword fallback) with **23 unit + 4 E2E tests** and streaming LLM responses in production, by implementing Pinecone embeddings, Next.js APIs, authentication, and usage analytics.
| | |
|:--|:--|
| **Impact** | Students find relevant professors by meaning, not just name or department strings |
| **Stack** | Next.js · Node.js · Pinecone · OpenAI (GPT-4o-mini) · Playwright · Vitest · CI · Vercel |
| **Links** | [Website](https://professor-match-ai.vercel.app/) · [Code](https://github.com/Arlikhozhaev/RateMyProfessor-RAG) |

---

## How I build (XYZ)
- **Raised release confidence across 3 production apps**, measured by **113+ automated tests** and CI on every push, by writing unit, API, and E2E coverage around core user and pipeline flows. 
- **Shortened time-to-insight for review data**, measured by one-click CSV upload → themed summary in a single session, by designing async analysis pipelines and persistent report storage. 
- **Prevented unsafe LLM output from shipping**, measured by **5 validation gates** blocking PRs unless syntax, lint, security, diff, and pytest checks pass, by treating model output as untrusted until structurally verified.  
- **Reduced irrelevant RAG answers**, measured by layered fallback retrieval when vector search underperforms, by combining Pinecone similarity, semantic re-ranking, and keyword search.  
- **Kept long-running work off the request thread**, measured by sub-second API responses while clone/analyze/refactor runs for minutes, by offloading pipelines to Celery workers with live task polling.

---

## Tech stack

### Languages
<table>
<tr>
<td align="center" width="120">
  <a href="https://www.typescriptlang.org/" title="Typed JavaScript — helps catch bugs before production">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="36" height="36"/><br/>
    <b>TypeScript</b><br/>
    <sub>Typed web code</sub>
  </a>
</td>
<td align="center" width="120">
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" title="The language that powers interactive websites">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="36" height="36"/><br/>
    <b>JavaScript</b><br/>
    <sub>Web interactivity</sub>
  </a>
</td>
<td align="center" width="120">
  <a href="https://www.python.org/" title="General-purpose language — great for data and backends">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="36" height="36"/><br/>
    <b>Python</b><br/>
    <sub>Scripts & data</sub>
  </a>
</td>
<td align="center" width="120">
  <a href="https://www.java.com/" title="Widely used language for large applications">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="36" height="36"/><br/>
    <b>Java</b><br/>
    <sub>Backend apps</sub>
  </a>
</td>
<td align="center" width="120">
  <a href="https://isocpp.org/" title="Fast systems language — performance-critical code">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="36" height="36"/><br/>
    <b>C++</b><br/>
    <sub>Performance</sub>
  </a>
</td>
</tr>
</table>

### Web & apps
<table>
<tr>
<td align="center" width="120">
  <a href="https://nextjs.org/" title="React framework for fast, production-ready websites">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="36" height="36"/><br/>
    <b>Next.js</b><br/>
    <sub>Full-stack web</sub>
  </a>
</td>
<td align="center" width="120">
  <a href="https://react.dev/" title="UI library for building interactive interfaces">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="36" height="36"/><br/>
    <b>React</b><br/>
    <sub>User interfaces</sub>
  </a>
</td>
<td align="center" width="120">
  <a href="https://nodejs.org/" title="JavaScript runtime for servers and APIs">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="36" height="36"/><br/>
    <b>Node.js</b><br/>
    <sub>Server & APIs</sub>
  </a>
</td>
</tr>
</table>

### Data, cloud & tools
<table>
<tr>
<td align="center" width="120">
  <a href="https://www.postgresql.org/" title="Reliable database for storing app data">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="36" height="36"/><br/>
    <b>PostgreSQL</b><br/>
    <sub>App database</sub>
  </a>
</td>
<td align="center" width="120">
  <a href="https://aws.amazon.com/" title="Cloud platform for hosting and scaling apps">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" width="36" height="36"/><br/>
    <b>AWS</b><br/>
    <sub>Cloud hosting</sub>
  </a>
</td>
<td align="center" width="120">
  <a href="https://vercel.com/" title="Deploys web apps quickly with minimal setup">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vercel/vercel-original.svg" width="36" height="36"/><br/>
    <b>Vercel</b><br/>
    <sub>Live deploys</sub>
  </a>
</td>
<td align="center" width="120">
  <a href="https://git-scm.com/" title="Version control — tracks every code change">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="36" height="36"/><br/>
    <b>Git</b><br/>
    <sub>Code history</sub>
  </a>
</td>
<td align="center" width="120">
  <a href="https://www.terraform.io/" title="Infrastructure as code — reproducible cloud setup">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" width="36" height="36"/><br/>
    <b>Terraform</b><br/>
    <sub>Cloud setup</sub>
  </a>
</td>
</tr>
</table>

<p align="center"><sub>
  <b>Also in my projects:</b> Prisma · OpenAI API · SQLite · MUI · Tailwind CSS · Playwright · Vitest · GitHub Actions
</sub></p>

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/arlikhozhaev)
[![Email](https://img.shields.io/badge/Email-arlikhozhaevca@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arlikhozhaevca@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-arlikhozhaev.dev-000?style=for-the-badge&logo=googlechrome&logoColor=white)](https://arlikhozhaev.dev)

---
