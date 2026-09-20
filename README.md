<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=200&section=header&text=BACKEND%20%26%20AI%20SYSTEMS&fontSize=38&fontColor=ffffff&animation=fadeIn&desc=Go%20%7C%20Applied%20AI%20Infrastructure%20%7C%20Research-bound&descSize=16&descAlignY=62" width="100%"/>

</div>

<h1 align="center">Hi 👋, I'm Rahimul</h1>
<h3 align="center">Building backend systems in Go — with an eye on MCP & Information Retrieval research</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=MdRahimulHassan&label=Profile%20views&color=0e75b6&style=flat" alt="profile views"/>
  <a href="https://github.com/MdRahimulHassan?tab=repositories">
    <img src="https://img.shields.io/badge/Follow-%40MdRahimulHassan-181717?style=flat&logo=github"/>
  </a>
</p>

---

### 🧭 About Me

- 🎓 Final-year **Software Engineering** student at **SUST**, Sylhet, Bangladesh &nbsp;|&nbsp; CGPA 3.62/4.00
- 🛠️ Specializing in **Go-based backend systems** and **applied AI infrastructure**
- 🧪 Currently building:
  - A **Codeforces MCP Server** — exposes the Codeforces API as tools for MCP-compatible AI clients
  - A fully local **Personal RAG system** in Go
  - A real-time **chat application** in Go
- 🧠 Long-term goal: landing a role at a **top tech giant**
- 🏛️ Executive Member, **SUST SWE Society** &nbsp;|&nbsp; Vice President, **Jamalpur Association**
- 💬 Ask me about: Go, MCP servers, RAG pipelines, distributed systems, competitive programming
- 📫 Reach me: **ndc12112026@gmail.com**
- ⚡ Fun fact: *Debugging is like being the detective in a crime movie where you're also the murderer.*

---

### 🧩 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**🔌 Codeforces MCP Server**

A Model Context Protocol server, written in Go, exposing the Codeforces API as tools for any MCP client (Claude Desktop, Claude Code, etc.).

- `get_problem` — look up a problem by contest ID + index
- `get_user_rating` — a handle's rating, max rating, rank
- `get_user_submissions` — recent submissions with verdicts
- `recommend_problem_by_rating` — unsolved problems within ±100 of a target rating, filterable by tags

Core Codeforces logic is fully decoupled from the MCP wiring, with standalone unit tests (`httptest`-mocked, no live network needed). The recommendation engine is an intentionally transparent rating-window heuristic — explainable and debuggable over a black-box model.

**[→ View repo](https://github.com/MdRahimulHassan/Codeforces-MCP-Server)**

</td>
<td width="50%" valign="top">

**📚 Personal RAG System**

A fully local Retrieval-Augmented Generation system built in Go — no external API dependency for inference.

- **Ingestion:** PDF parsing pipeline
- **Embeddings:** Ollama running `mxbai-embed-large`
- **Storage:** pgvector in Docker
- **Backend:** Go HTTP API
- **Frontend:** vanilla JS

Includes an LLM-as-judge evaluation system to assess retrieval and answer quality, rather than relying on manual spot-checks — a small but deliberate step toward measurable RAG quality.

**[→ View repo](hhttps://github.com/MdRahimulHassan/Personal-RAG)**

</td>
</tr>
</table>

---

### 🔗 Connect with Me

<p align="center">
  <a href="https://www.linkedin.com/in/rahimul-hasan-98bb31300/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:ndc12112026@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

---

### 🧰 Languages & Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,c,cpp,java,python,docker,linux,git,github,vscode,postgres,redis&perline=6"/>
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=MdRahimulHassan&show_icons=true&theme=tokyonight&hide_border=true"/>
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=MdRahimulHassan&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MdRahimulHassan&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=MdRahimulHassan&theme=tokyo-night&hide_border=true"/>
</p>

### 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MdRahimulHassan/MdRahimulHassan/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MdRahimulHassan/MdRahimulHassan/output/github-contribution-grid-snake.svg" />
    <img alt="github contribution snake animation" src="https://raw.githubusercontent.com/MdRahimulHassan/MdRahimulHassan/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=100&section=footer" width="100%"/>