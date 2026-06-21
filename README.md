<!-- ====================== HEADER ====================== -->
<a href="#">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FEB,100:0D1117&height=200&section=header&text=Tim%20Betz&fontSize=62&fontColor=ffffff&fontAlignY=36&desc=Building%20AI%20agents%20that%20turn%20language%20into%20running%20systems&descSize=18&descAlignY=58&animation=fadeIn" alt="Tim Betz" />
</a>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&width=620&lines=AI+Agent+Engineer+%26+Automation+Builder;Claude+Agent+SDK+%C2%B7+MCP+%C2%B7+Knowledge+Graphs;Python+%7C+TypeScript+%7C+FastAPI+%7C+n8n;Turning+natural+language+into+live+systems)](https://github.com/timbtz)

<br/>

![Location](https://img.shields.io/badge/Munich,%20Germany-30363D?style=for-the-badge&logo=googlemaps&logoColor=58A6FF)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tim-betz-358137345/)
![Profile Views](https://komarev.com/ghpvc/?username=timbtz&style=for-the-badge&color=1F6FEB&label=PROFILE+VIEWS)

</div>

---

## 👋 About Me

```ts
const tim = {
  role:    "B.Sc. Management & Technology @ TUM (Computer Engineering focus)",
  focus:   ["AI agents", "MCP servers", "agentic systems", "knowledge graphs"],
  building:"infrastructure where you describe intent and the system plans, validates & ships it",
  current: ["Knowledge-graph engineering @ KI Reply",
            "Agentic-systems research @ ETH Agentic Systems Lab"],
  stack:   "Anthropic Claude Agent SDK · Model Context Protocol · n8n · Make.com",
  based:   "Munich, Germany 🇩🇪",
};
```

I build **AI-native automation** and **agent memory systems** — primarily around the **Claude Agent SDK** and the **Model Context Protocol (MCP)**. Most of my projects share a thesis: keep the deterministic parts deterministic, use LLMs surgically, and make every decision **auditable**.

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**AI · Agents · Retrieval**

![Anthropic](https://img.shields.io/badge/Claude%20Agent%20SDK-191919?style=for-the-badge&logo=anthropic&logoColor=D97757)
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![FastMCP](https://img.shields.io/badge/FastMCP-009688?style=for-the-badge)
![Graphiti](https://img.shields.io/badge/Graphiti-6E56CF?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-30363D?style=for-the-badge)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)

**Backend · Data · Graph**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![FalkorDB](https://img.shields.io/badge/FalkorDB-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

**Frontend · Automation · Infra**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Make](https://img.shields.io/badge/Make.com-6D00CC?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-1A1A1A?style=for-the-badge&logo=linux&logoColor=FCC624)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [Agent Harness](https://github.com/timbtz/Agent-harness)
**Persistent memory for AI coding agents.** An open-source MCP server that captures decisions, insights and architecture as a **temporal knowledge graph** (Graphiti + FalkorDB), so Claude Code starts every session already knowing what happened before. Hybrid recall (cosine + BM25 + graph BFS via RRF) and a **Three.js time-scrubber** to replay the graph at any past date.

`TypeScript` · `Python` · `FastMCP` · `Graphiti` · `FalkorDB` · `React Three Fiber`

</td>
<td width="50%" valign="top">

### ⚙️ [Make Vibecoder](https://github.com/timbtz/make-vibecoder)
**Describe an automation, get a live Make.com scenario.** A full AI-native automation-engineering stack: a context-efficient MCP server (~50-line tool outputs vs 120–200 raw), 266 blueprint templates + 502 indexed module examples, a **5-pass offline validator**, and auto-healing deployment. Published to npm as `make-mcp-server`.

`TypeScript` · `Claude Agent SDK` · `MCP` · `SQLite FTS5` · `Zod`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔬 [Agnes](https://github.com/timbtz/Spherecast-Agnes) · _TUM.ai × Spherecast_
**Agentic supply-chain intelligence for supplement brands.** Enriches SKU/BOM data against 6 public bio/chem APIs (PubChem, DSLD, openFDA, GLEIF, USDA FDC, Molport), then finds cross-company consolidation opportunities via **declarative YAML DAG pipelines**. Compound-intent routing, a 4-state compliance gate, and an optional ElevenLabs voice UI.

`Python` · `FastAPI` · `React` · `Claude` · `Gemini` · `SQLite`

</td>
<td width="50%" valign="top">

### 💶 [Fingent](https://github.com/timbtz/HEC-Paris) · _Paris Fintech Hackathon_
**AI-assisted accounting that stays auditable.** A YAML-driven DAG executor that books every transaction via deterministic rules, cached lookups, then Claude — recording *how* (rule/cache/AI-confidence) and *by whom* for each decision. Self-improving **rule wiki**, integer-cent ledger, and one `GROUP BY` to attribute any vendor invoice.

`Python` · `FastAPI` · `Claude` · `shadcn/ui` · `Swan API` · `SQLite`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📈 [GraphRetr](https://github.com/timbtz/RL-on-codefunction-in-a-GraphRAG) · _ETH Agentic Systems Lab_
**RL that rewrites retrieval code over a frozen knowledge graph.** Loads STaRK-prime (129k nodes / 8.1M edges) into FalkorDB, then optimizes `search(q, G)` programs via program mutation and **multi-objective (Pareto) reward** over Recall@20 / MRR / nDCG — with MLflow tracking and checkpoint/resume.

`Python` · `FalkorDB` · `MLflow` · `PyTorch` · `sentence-transformers`

</td>
<td width="50%" valign="top">

### 📊 [Celonis × Make × Claude](https://github.com/timbtz/Celonis-analyst-Flow-via-Make.com-)
**Ask O2C process-mining questions in Slack.** A two-scenario agent: a Knowledge-Model auto-discovery flow generates a system prompt from live Celonis data, and a Slack query agent answers KPI questions against it in natural language.

`Make.com` · `Celonis` · `Claude Sonnet` · `Slack` · `Google Sheets`

</td>
</tr>
</table>

> **Also:** a **RAG-powered lead-enrichment pipeline** — n8n orchestration + self-hosted Supabase (Postgres + pgvector) on a Hetzner VPS, feeding an LLM email-drafting agent.

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=timbtz&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&text_color=adbac7" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=timbtz&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=adbac7" />

<br/>

<img height="170" src="https://streak-stats.demolab.com/?user=timbtz&hide_border=true&background=0D1117&stroke=58A6FF&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF&sideLabels=adbac7&dates=8b949e&currStreakNum=adbac7&sideNums=adbac7" />

</div>

---

<div align="center">

### 🤝 Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tim-betz-358137345/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/timbtz)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:1F6FEB&height=120&section=footer&reversal=true" alt="footer" />
