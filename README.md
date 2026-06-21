<!-- ====================== HEADER ====================== -->
<a href="#">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FEB,100:0D1117&height=200&section=header&text=Tim%20Betz&fontSize=62&fontColor=ffffff&fontAlignY=36&desc=Agent%20memory,%20knowledge%20graphs%20%26%20retrieval%20optimization&descSize=18&descAlignY=58&animation=fadeIn" alt="Tim Betz" />
</a>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&width=640&lines=Agentic+Systems+Engineer;Agent+Memory+%C2%B7+Temporal+Knowledge+Graphs;Graph+Retrieval+%C2%B7+RL+%C2%B7+Multi-objective+Optimization;Python+%7C+TypeScript+%7C+FalkorDB+%7C+PyTorch)](https://github.com/timbtz)

<br/>

![Location](https://img.shields.io/badge/Munich,%20Germany-30363D?style=for-the-badge&logo=googlemaps&logoColor=58A6FF)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tim-betz-358137345/)

</div>

---

## 👋 About Me

I work on the **infrastructure layer of AI agents** — how they **remember**, how they **retrieve**, and how they **orchestrate** multi-step work without losing auditability. That means temporal knowledge graphs as agent memory, hybrid retrieval (vector + lexical + graph traversal), and reinforcement learning that optimizes the *retrieval program itself*. My recurring thesis: keep the deterministic parts deterministic, use LLMs surgically, and make **every decision traceable**.

- 🎓 &nbsp;B.Sc. Management & Technology @ **TUM** — Computer Engineering focus
- 🔭 &nbsp;Currently doing **knowledge-graph engineering @ KI Reply**
- ⚡ &nbsp;Deep into temporal knowledge graphs, RL for retrieval, multi-objective optimization & auditable agent pipelines
- 🤖 &nbsp;Coding agents I run daily: **Claude Code** & **Pi**
- 🧰 &nbsp;Comfort zone: Claude Agent SDK · MCP · Graphiti · Neo4j · FalkorDB · FastAPI
- 📍 &nbsp;Based in **Munich, Germany** 🇩🇪

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**AI Agents · MCP**

![Claude Agent SDK](https://img.shields.io/badge/Claude%20Agent%20SDK-191919?style=for-the-badge&logo=anthropic&logoColor=D97757)
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![FastMCP](https://img.shields.io/badge/FastMCP-009688?style=for-the-badge)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Pi](https://img.shields.io/badge/Pi%20Agent-30363D?style=for-the-badge)

**Knowledge Graphs · Retrieval · ML**

![Graphiti](https://img.shields.io/badge/Graphiti-6E56CF?style=for-the-badge)
![FalkorDB](https://img.shields.io/badge/FalkorDB-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white)
![RAG](https://img.shields.io/badge/RAG%20%2F%20Hybrid%20Search-30363D?style=for-the-badge)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Sentence Transformers](https://img.shields.io/badge/Sentence--Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)

**Backend · Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-1A1A1A?style=for-the-badge&logo=linux&logoColor=FCC624)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 📈 [GraphRetr](https://github.com/timbtz/RL-on-codefunction-in-a-GraphRAG)
**RL that rewrites the retrieval program itself.** Loads STaRK-prime (129k nodes / 8.1M edges) into FalkorDB with per-type vector indexes, then mutates chains of 7 retrieval DSL primitives (`search` · `rerank` · `filter` · `expand` · …) to improve `search(q, G)`. Scored by **multi-objective Pareto reward** over Recall@20 / MRR / nDCG with **MAP-Elites** archiving — graph and LLM weights stay frozen, only the program evolves. MLflow tracking + checkpoint/resume.

`Python` · `FalkorDB` · `PyTorch` · `MLflow` · `sentence-transformers`

</td>
<td width="50%" valign="top">

### 🧠 [Agent Harness](https://github.com/timbtz/Agent-harness)
**Durable, structured memory for AI coding agents.** An open-source MCP server that extracts decisions and architecture into a **temporal knowledge graph** (Graphiti + FalkorDB), so Claude Code starts each session aware of what came before. Recall fuses **cosine + BM25 + graph BFS** via reciprocal-rank fusion; async extraction with per-project graph isolation; a **React Three Fiber time-scrubber** replays the graph at any past date.

`TypeScript` · `Python` · `FastMCP` · `Graphiti` · `FalkorDB` · `RRF`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔬 [Agnes](https://github.com/timbtz/Spherecast-Agnes) · _TUM.ai × Spherecast_
**Agentic supply-chain intelligence.** A **YAML-defined DAG orchestration engine** (Kahn topological sort + asyncio parallelism) runs enrichment against 6 bio/chem APIs, then mines cross-company consolidation opportunities. Compound-intent routing fans one query into parallel pipelines with independent SSE streams; a 4-state compliance gate and event-sourced log make every recommendation auditable.

`Python` · `FastAPI` · `React` · `Claude` · `Gemini` · `SQLite`

</td>
<td width="50%" valign="top">

### 💶 [Fingent](https://github.com/timbtz/HEC-Paris) · _Paris Fintech Hackathon_
**Deterministic-first, auditable AI accounting.** A YAML-driven DAG executor books each transaction via rules → cache → Claude, recording *how* (rule / cache / AI-confidence) and *by whom*. A self-improving **rule wiki** with **prompt-hash invalidation** maps a policy edit to exactly the agent calls it affects; an invariant checker enforces hard ledger guarantees on an integer-cent store.

`Python` · `FastAPI` · `Claude` · `shadcn/ui` · `Swan API` · `SQLite`

</td>
</tr>
</table>

---

## 🎧 In My Ears

<div align="center">

[![20VC](https://img.shields.io/badge/20VC-1DB954?style=for-the-badge&logo=spotify&logoColor=white)](https://open.spotify.com/show/3j2KMcZTtgTNBKwtZBMHvl)
[![Latent Space](https://img.shields.io/badge/Latent%20Space-1DB954?style=for-the-badge&logo=spotify&logoColor=white)](https://open.spotify.com/show/2p7zZVwVF6Yk0Zsb4QmT7t)
![AI Engineer](https://img.shields.io/badge/AI%20Engineer-1DB954?style=for-the-badge&logo=spotify&logoColor=white)
[![Founder Mode](https://img.shields.io/badge/Founder%20Mode-1DB954?style=for-the-badge&logo=spotify&logoColor=white)](https://open.spotify.com/show/1I00imiolVQ4TxtBW0yOyW)

</div>

---

<div align="center">

### 🤝 Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tim-betz-358137345/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/timbtz)

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:1F6FEB&height=120&section=footer&reversal=true" alt="footer" />
