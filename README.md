<!-- ============ HEADER ============ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:f9a8d4,50:ec4899,100:c084fc&text=Maryam%20Moeed&fontColor=ffffff&fontSize=56&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20Multi-Agent%20LLM%20Systems&descAlignY=58&descSize=18&animation=fadeIn" width="100%" alt="Maryam Moeed — AI Engineer"/>
</p>

<p align="center">
  <a href="https://github.com/maryammoeed">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3200&pause=900&color=DB2777&center=true&vCenter=true&width=720&lines=AI+Engineer+building+multi-agent+LLM+systems.;Guardrails+%C2%B7+evaluation+%C2%B7+retrieval.;Human-in-the-loop+oversight+for+agentic+AI.;Federated+learning+for+rare+disease+research." alt="Typing intro"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/maryam-moeed-752631247"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:maryammoeed68@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <!-- PORTFOLIO-BADGE: added once the Vercel site is live -->
  <img src="https://komarev.com/ghpvc/?username=maryammoeed&style=for-the-badge&color=ec4899&label=PROFILE+VIEWS" alt="Profile views"/>
</p>

<p align="center">
  <img src="./assets/street-walk.svg" width="100%" alt="Animated pastel street: I walk past a café, office, workshop, lab and post office, and each one opens a part of my story. Click to walk through it yourself."/>
</p>

---

### 🧠 About me

```python
class Maryam:
    role        = "AI Engineer @ 10Pearls — multi-agent LLM systems in production"
    based_in    = "Islamabad, Pakistan"
    building    = ["multi-agent LLM pipelines", "guardrails & validation layers",
                   "human-in-the-loop review", "LLM evaluation & observability"]
    supervising = "GIKI undergrad team — federated learning + blockchain for rare disease research"
    researching = ["multi-agent coordination", "reliability & safety of agentic AI",
                   "human oversight of autonomous pipelines", "privacy-preserving ML for healthcare"]
    education   = "BS Computer Science, FAST-NUCES — Dean's List (Fall 2023)"

    def current_question(self):
        return "Where should a human step into a long agent chain — and how do we know the agents got it right?"
```

### ⚙️ What I build

<p align="center">
  <img src="./assets/agent-pipeline.svg" width="100%" alt="Animated pipeline: input → platform kickoff form → Python use case (files embedded into a knowledge base) → input guardrails → agents with retrieval → evaluator agent (fail → retry, max 3) → output guardrails → validated response; results return to the platform via Azure Service Bus, with Application Insights monitoring every stage"/>
</p>

Two years shipping production agent systems in a regulated domain, where outputs have to be **correct, compliant and explainable**:

- **Platform ↔ use case** — users start a run through a kickoff form on the platform; a Python use-case service picks it up and orchestrates the agents, sending status and results back to the platform over **Azure Service Bus**
- **Retrieval** — uploaded files are embedded into a knowledge base so agents can answer questions from the client's own documents
- **Input guardrails** — every input is screened for secrets and prompt injection before it reaches an agent
- **Evaluator loop** — an evaluator agent checks each output against defined rules; anything that fails goes back to the agent, with up to 3 retries
- **Output guardrails** — final responses are checked for toxic language and leaked secrets before they're returned
- **Observability** — **Application Insights** collects logs and traces from every stage for monitoring and debugging
- **Shipping** — async FastAPI on Azure Container Apps with automated CI/CD

---

### 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### 📐 LOE Estimation System
Three-stage reasoning pipeline (few-shot → chain-of-thought → structured output) that turns project documents into architecture, work breakdown and FTE estimates, with retrieval-based validation at every stage.

`GPT-4o` `LangChain` `Pinecone`

</td>
<td width="50%" valign="top">

#### 🤖 MentorBot
A self-improving RAG assistant: unanswered questions escalate to human mentors and their answers are ingested automatically. Also automates multi-language PR review that blocks merges until issues are fixed.

`LangChain` `ChromaDB` `Discord API` `GitHub API`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 💼 HR Assistant
Organization-wide RAG assistant on Microsoft Teams with validated structured outputs; Langfuse traces used to cut latency and prompt cost.

`Azure` `FastAPI` `Pydantic AI` `ChromaDB` `Langfuse`

</td>
<td width="50%" valign="top">

#### 🚶 Biometric Gait Recognition
Final-year research: PCA + LDA + Maximum Margin Criterion on CMU MoCap sequences — **95.3% CCR** at roughly **1/19th** the compute of PCA/LDA alone.

`Subspace learning` `Python` `CMU MoCap`

</td>
</tr>
</table>

<!-- Tip: link each project title to its repo, e.g. #### [🤖 MentorBot](https://github.com/maryammoeed/REPO) -->

---

### 🧭 Journey

| When | Role | Where |
|---|---|---|
| Aug 2025 – now | **AI Engineer** — production multi-agent LLM systems | 10Pearls |
| Aug 2025 – May 2026 | **Project Supervisor** — federated learning + blockchain for rare disease research | GIKI |
| Jun – Sep 2025 | **AI / Data Science Mentor** | Code for Pakistan |
| Aug 2024 – Jul 2025 | **Associate AI Engineer** — 4+ production LLM systems, team-wide Langfuse evaluation practice | 10Pearls |
| Jul – Nov 2023 | **Data Science Intern** — warehouse digital twin (Prophet + SimPy), PuLP inventory optimization | Royal Cyber |
| 2020 – 2024 | **BS Computer Science** — Dean's List, Fall 2023 | FAST-NUCES |

🏆 Employee of the Month ×2 · Team of the Quarter ×1 at 10Pearls

---

### 🛠️ Tech stack

**Agentic AI & LLMs**
<p>
  <img src="https://img.shields.io/badge/CrewAI-FF5A50?style=flat-square&logoColor=white" alt="CrewAI"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/Pydantic_AI-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="Pydantic AI"/>
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/Unsloth-111833?style=flat-square" alt="Unsloth"/>
  <img src="https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square" alt="Langfuse"/>
</p>

**Retrieval & data**
<p>
  <img src="https://img.shields.io/badge/Pinecone-000000?style=flat-square" alt="Pinecone"/>
  <img src="https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square" alt="ChromaDB"/>
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square" alt="Qdrant"/>
  <img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white" alt="Neo4j"/>
  <img src="https://img.shields.io/badge/Cosmos_DB-0078D4?style=flat-square" alt="Cosmos DB"/>
</p>

**ML, systems & cloud**
<p>
  <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,fastapi,flask,nodejs,docker,kubernetes,azure,aws,postgres,mongodb,git,linux&perline=14" alt="Python, PyTorch, TensorFlow, FastAPI, Flask, Node.js, Docker, Kubernetes, Azure, AWS, PostgreSQL, MongoDB, Git, Linux"/>
</p>

---

### 📊 GitHub activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=maryammoeed&show_icons=true&hide_border=true&bg_color=fff0f7&title_color=be185d&icon_color=ec4899&text_color=4a1d3a&include_all_commits=true&count_private=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=maryammoeed&layout=compact&hide_border=true&bg_color=fff0f7&title_color=be185d&text_color=4a1d3a" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=maryammoeed&hide_border=true&background=fff0f7&ring=ec4899&fire=f472b6&currStreakLabel=be185d&sideLabels=4a1d3a&currStreakNum=831843&sideNums=831843&dates=8b5a78" alt="GitHub streak"/>
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=maryammoeed&bg_color=fff0f7&color=be185d&line=ec4899&point=c084fc&area=true&area_color=f9a8d4&hide_border=true" alt="Contribution graph"/>
</p>

---

<p align="center">
  <i>Open to conversations about agentic AI reliability, human-in-the-loop systems, and privacy-preserving ML for healthcare.</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:c084fc,50:ec4899,100:f9a8d4" width="100%" alt=""/>
</p>
