<div align="center">
  <h1>Gopesh Pandey</h1>
  <h3>Software Engineer | AI, Machine Learning & Backend Systems</h3>
  <p>B.Tech Computer Science (AI & ML) @ VIT-AP University (2022–2026)</p>
</div>

<div align="center">
  <a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/gopesh-pandey-50a601258/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</div>

---

I am a software engineer focused on building low-latency backend systems and production-ready Artificial Intelligence pipelines. I specialize in Machine Learning, robust LLM integrations (RAG), and writing extensively tested, scalable code. I actively debug and contribute to enterprise-grade open-source repositories to improve system reliability.

## Technical Expertise

- **Languages:** Python, Java, SQL
- **Machine Learning & AI:** Machine Learning, Deep Learning, PyTorch, LLMs, RAG, LangChain, LlamaIndex
- **Backend Infrastructure:** FastAPI, Flask, REST API Design, Vector Databases (Pinecone/Chroma), PostgreSQL
- **Cloud & DevOps:** AWS, Docker, Git, GitHub Actions, CI/CD, Unit Testing (Pytest, Unittest)

---

## Featured Architecture & Projects

**Enterprise RAG Document Search System**
- **Domain:** Applied AI & Backend
- **Impact:** Engineered an AI-powered Retrieval-Augmented Generation (RAG) system capable of querying and extracting precise context from 10,000+ dense documents with sub-100ms latency.
- **Tech:** Python, LangChain, Vector Databases, Machine Learning.

**Guardian Gate System Architecture**
- **Domain:** Backend & System Design
- **Impact:** Designed a highly scalable backend architecture focusing on secure request routing, API gateways, and efficient load management to handle high-throughput network traffic.
- **Tech:** Backend Architecture, API Security, System Design.

---

## Open Source Engineering

### Core Infrastructure & Reliability

**LangChain (langchain-ai)**
- **Engineering:** Resolved a critical crash in `ChatOllama` caused by malformed JSON during tool calling streams. Wrapped the async generator to catch `ResponseError`, allowing the agent loop to gracefully recover and process raw text instead of hard-failing.
- **Testing:** Validated recovery logic with comprehensive pytest suites.
- **Status:** Active PR (#35201)

**AWS CLI (aws)**
- **Engineering:** Prevented configuration corruption by modifying the config writing logic to skip empty or whitespace-only inputs (e.g., `region =`). Preserved expected behavior for valid inputs across the CLI ecosystem.
- **Testing:** Authored rigorous unit tests adhering to strict AWS `unittest` standards.
- **Status:** Active PR (#10003)

**LlamaIndex**
- **Engineering:** Investigated Mem0 memory integration behavior with multiple context identifiers. Proposed architectural adjustments during technical reviews with core maintainers, driving an upstream system refactor.

### Algorithms & Mathematical Implementations

**TheAlgorithms/Java (~65k Stars) & keon/algorithms (~25k Stars)**
- **Engineering:** Implemented foundational algorithms (Euclidean Distance, Torus Surface Area) in Java and Python. Ensured strict adherence to CI/CD pipelines, `clang-format` standards, and mathematical correctness.
- **Status:** 3 PRs Merged (#7218, #2713, #2714)

---

### GitHub Analytics

<div align="center">
  <img height="195" src="https://github-readme-stats.vercel.app/api?username=Gopesh111&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&v=1" alt="Gopesh's GitHub Stats" />
  <img height="195" src="https://github-readme-streak-stats.herokuapp.com/?user=Gopesh111&theme=dark&hide_border=true&background=0d1117&v=1" alt="Gopesh's GitHub Streak" />
</div>
