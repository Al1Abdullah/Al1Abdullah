<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    HEADER BANNER                          -->
<!-- ═══════════════════════════════════════════════════════════ -->
<div align="center">
  <img src="assets/header.png" width="100%" alt="Ali Abdullah — AI Engineering Student"/>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    TYPING ANIMATION                       -->
<!-- ═══════════════════════════════════════════════════════════ -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Segoe+UI&weight=600&size=19&duration=3200&pause=1000&color=AEB06F&background=00000000&center=true&vCenter=true&width=620&lines=AI+Engineering+Student+%40+SZABIST%2C+Islamabad;Building+Helix%2C+an+MCP+Clinical+Evidence+Engine;Retrieval-Augmented+Systems+%26+Applied+CV;Always+Learning+%E2%80%94+Always+Shipping" alt="Typing SVG"/>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    ABOUT                                  -->
<!-- ═══════════════════════════════════════════════════════════ -->
<div align="center">

### 👋 &nbsp;About Me

</div>

Most of what I build sits between a trained model and something a person could actually use — data pipelines, retrieval systems, APIs, and the deployment work that turns an experiment into a running service.

A lot of my recent work centers on retrieval-augmented generation and information retrieval more broadly. **Helix**, for instance, is a clinical evidence engine that queries ClinicalTrials.gov, PubMed, NLM MeSH, and openFDA in parallel, then scores and ranks the combined results using BM25 and eligibility filtering — so it's clear *why* a result was ranked where it was, not just *that* it was. I've also worked on computer vision, with a plant disease classifier built on a fine-tuned MobileNetV2, and on tooling that wraps common ML workflows into something usable from a browser.

In mid-2025, I worked as an **AI Intern at atomcamp**, where I built a RAG-based knowledge assistant over the company's program and admissions data, along with an AutoML tool for CSV-based workflows — both deployed on Hugging Face Spaces.

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    CURRENTLY                              -->
<!-- ═══════════════════════════════════════════════════════════ -->
<div align="center">

### 🚧 &nbsp;Currently

</div>

- 🎓 Studying AI Engineering at SZABIST, Islamabad *(expected 2027)*
- 🧪 Building **Helix** — an MCP-compatible clinical evidence retrieval engine
- 🌍 Open to AI/ML internships in Islamabad, on-site preferred

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    FEATURED PROJECTS                      -->
<!-- ═══════════════════════════════════════════════════════════ -->
<div align="center">

### 🚀 &nbsp;Featured Projects

</div>

<table width="100%">
<tr>
<td width="50%" valign="top">

**🩺 Helix**

A clinical evidence synthesis engine and MCP (Model Context Protocol) server that queries ClinicalTrials.gov, PubMed, NLM MeSH, and openFDA in parallel, then ranks the combined results using BM25-based scoring with eligibility filtering. Every result includes a breakdown of how it was scored, and multi-source queries run asynchronously so they don't block on each other.

<img src="https://img.shields.io/badge/Python-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/FastAPI-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/MCP-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/AsyncIO-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/Docker-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/>

</td>
<td width="50%" valign="top">

**🌿 Plantoi**

A plant disease classifier that takes a photo of a leaf and returns a likely diagnosis along with treatment guidance. The core model is a MobileNetV2 fine-tuned across 38 disease classes, served through a Flask app and deployed as a Docker container on Hugging Face Spaces, with a lightweight AI layer for follow-up questions about the diagnosis.

<img src="https://img.shields.io/badge/Python-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/TensorFlow-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/Flask-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/Docker-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/HF_Spaces-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📚 RAG Knowledge Assistant — atomcamp**

A document-grounded chatbot built during my internship to answer questions about atomcamp's programs, courses, and admissions process. Runs a full RAG pipeline — ingestion, chunking, Qdrant for vector storage, Hugging Face embeddings, and MMR-based retrieval to keep results diverse. I've since revisited the chunking and embedding approach to improve retrieval quality.

<img src="https://img.shields.io/badge/Python-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/LangChain-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/Qdrant-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/FastAPI-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/Groq-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/>

</td>
<td width="50%" valign="top">

**📊 AutoML**

A browser-based tool that runs a CSV dataset through a full ML workflow — preprocessing, model training, evaluation, and visualization — with an AI assistant on top for asking questions about the dataset and results. Built to cut down on the repetitive setup that comes with exploring a new dataset.

<img src="https://img.shields.io/badge/Python-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/Flask-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/Scikit_learn-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/XGBoost-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/CatBoost-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/> <img src="https://img.shields.io/badge/PyCaret-35542C?style=for-the-badge&logoColor=AEB06F&labelColor=030B0D"/>

</td>
</tr>
</table>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    GITHUB STATS                           -->
<!-- ═══════════════════════════════════════════════════════════ -->
<div align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=Al1Abdullah&show_icons=true&theme=transparent&bg_color=030B0D&title_color=AEB06F&text_color=C2C2BD&icon_color=35542C&border_color=35542C&include_all_commits=true&count_private=true"
    height="175" alt="GitHub Stats"/>
  &nbsp;&nbsp;
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=Al1Abdullah&layout=compact&theme=transparent&bg_color=030B0D&title_color=AEB06F&text_color=C2C2BD&border_color=35542C&langs_count=8"
    height="175" alt="Top Languages"/>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    STREAK STATS                           -->
<!-- ═══════════════════════════════════════════════════════════ -->
<div align="center">
  <img
    src="https://streak-stats.demolab.com/?user=Al1Abdullah&background=030B0D&ring=35542C&fire=AEB06F&currStreakLabel=C2C2BD&sideLabels=AEB06F&dates=C2C2BD&border=35542C&stroke=35542C&currStreakNum=C2C2BD&sideNums=C2C2BD"
    width="96%" alt="GitHub Streak"/>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    TECH STACK                             -->
<!-- ═══════════════════════════════════════════════════════════ -->
<div align="center">

### 🛠 &nbsp;Tech Stack

**Languages**

<img src="https://skillicons.dev/icons?i=python,js,html,css&theme=dark" alt="Languages"/>

**AI & ML**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv&theme=dark" alt="AI/ML"/>

**Infrastructure & Tools**

<img src="https://skillicons.dev/icons?i=fastapi,flask,docker,git,github,linux&theme=dark" alt="Tools"/>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    BACKGROUND                             -->
<!-- ═══════════════════════════════════════════════════════════ -->
<div align="center">

### 🎓 &nbsp;Background

</div>

**Education**
SZABIST University, Islamabad
Bachelor's degree, AI Engineering *(2023 – 2027)*
Coursework centered on machine learning and applied computing, with an emphasis on turning concepts into working implementations through projects and structured assignments.

**Experience**
AI Intern, atomcamp — *Jun 2025 to Aug 2025, Islamabad*
Built a RAG-based knowledge assistant and an AutoML tool for CSV-based workflows, both deployed on Hugging Face Spaces, and worked on prompt engineering to keep model outputs structured and consistent.

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    ACTIVITY GRAPH                         -->
<!-- ═══════════════════════════════════════════════════════════ -->
<div align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=Al1Abdullah&bg_color=030B0D&color=C2C2BD&line=35542C&point=AEB06F&area=true&area_color=35542C&hide_border=false&border_color=35542C&radius=6"
    width="96%" alt="Activity Graph"/>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    SNAKE ANIMATION                        -->
<!-- ═══════════════════════════════════════════════════════════ -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)"
            srcset="https://raw.githubusercontent.com/Al1Abdullah/Al1Abdullah/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)"
            srcset="https://raw.githubusercontent.com/Al1Abdullah/Al1Abdullah/output/github-contribution-grid-snake.svg"/>
    <img src="https://raw.githubusercontent.com/Al1Abdullah/Al1Abdullah/output/github-contribution-grid-snake-dark.svg"
         alt="Contribution Snake"/>
  </picture>
</div>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    GET IN TOUCH / FOOTER                  -->
<!-- ═══════════════════════════════════════════════════════════ -->
<br/>
<div align="center">

### 📫 &nbsp;Get in Touch

<a href="https://al1abdullah.netlify.app"><img src="https://img.shields.io/badge/Portfolio-AEB06F?style=for-the-badge&logoColor=030B0D&labelColor=030B0D&color=AEB06F"/></a>

<br/><br/>

  <img
    src="https://komarev.com/ghpvc/?username=Al1Abdullah&label=Profile+Views&color=35542C&style=flat-square"
    alt="Profile Views"/>
</div>
