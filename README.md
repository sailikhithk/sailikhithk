# Sai Likhith Kanuparthi

<p align="left">
  <img src="welcome-1.gif" width="220" height="132" align="right" />
  <a href="https://git.io/typing-svg">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=38BDF8&width=520&lines=Senior+AI+Infrastructure+%26+Systems+Engineer;LLM+Serving+Runtimes+%7C+Distributed+Observability;Enterprise+Agentic+Platforms+%40+Airbnb;Kafka+4M+req%2Fmin+%7C+OTel+%7C+vLLM+%7C+Bedrock">
      <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=0284c7&width=520&lines=Senior+AI+Infrastructure+%26+Systems+Engineer;LLM+Serving+Runtimes+%7C+Distributed+Observability;Enterprise+Agentic+Platforms+%40+Airbnb;Kafka+4M+req%2Fmin+%7C+OTel+%7C+vLLM+%7C+Bedrock">
      <img alt="Typing SVG" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=38BDF8&width=520&lines=Senior+AI+Infrastructure+%26+Systems+Engineer;LLM+Serving+Runtimes+%7C+Distributed+Observability;Enterprise+Agentic+Platforms+%40+Airbnb;Kafka+4M+req%2Fmin+%7C+OTel+%7C+vLLM+%7C+Bedrock" />
    </picture>
  </a>
</p>

> Senior AI Infrastructure & Systems Engineer. Building low-latency LLM serving runtimes, distributed observability (OTel/Prometheus), and enterprise agentic platforms.

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=sailikhithk&label=Profile%20views&color=7c3aed&style=flat" alt="Profile views" />&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/sailikhithk/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=Linkedin&logoColor=white" alt="Linkedin" /></a> 
  <a href="https://twitter.com/codewithsai"><img src="https://img.shields.io/badge/-X-000000?style=flat&logo=x&logoColor=white" alt="X" /></a> 
  <a href="https://github.com/sailikhithk/?tab=follow"><img src="https://img.shields.io/github/followers/sailikhithk?label=Follow&style=flat&logo=github&logoColor=white&color=24292e" alt="GitHub Followers" /></a> 
  <a href="mailto:sailikhithcse@gmail.com"><img src="https://img.shields.io/badge/-Gmail-D14836?style=flat&logo=Gmail&logoColor=white" alt="Gmail" /></a>
</p>


## Currently Building

**[llm-production-engineering](https://github.com/sailikhithk/llm-production-engineering)** - Field notes from building AI systems in production since 2019. The ops side of LLM serving: cost tracking, eval-driven deployment, capacity planning, observability, incident playbooks, and decision frameworks. Maps directly to my day job at Airbnb.

- Multi-tenant OTel cost tracking for LLM platforms (per-request, per-team, per-product attribution)
- Prefix-caching telemetry and cache-miss detection across Bedrock, OpenAI, Anthropic, vLLM
- Redis token bucket budgets for multi-tenant rate limiting
- Eval-driven deployment: 23+ agent versions, 1,690 versioned ground-truth samples, dual-model A/B testing


## About

- **Role:** Senior AI Infrastructure & Systems Engineer at **Airbnb**. I own end-to-end architecture and production rollout of the **BPI Virtual Analyst** platform - a multi-model GenAI orchestration system abstracting **30+ foundation models** (AWS Bedrock, OpenAI, Anthropic Claude, vLLM) behind **FacadeDriver** with routing, retry, fallback, and graceful degradation. Platform processes **10K rows per run and 40MB uploads** with PII-safe inference, serving **55+ analysts** across **4 partner engineering teams**.
- **Streaming & Batch:** Owned architecture and production operation of **Kafka pipelines sustaining 4M req/min** at Southwest Airlines with idempotent partition-keyed consumers, DLQ, and backpressure handling. Cut on-call **MTTR from 45 to 12 minutes** (73% reduction). Owned batch ETL on **Databricks and Azure Data Factory** at Shell with PySpark, Spark SQL, and Hive/Trino.
- **Observability:** OpenTelemetry collectors, Loki tracing (prompt, tool call, retrieval quality), Datadog, Grafana, drift detection, post-incident review. The same stack I open-source on in LangChain and LiveKit.
- **Research:** Published across **Cambridge Scholars Publishing** (2 book chapters, 2025), [IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/11004721), [SPE ADIPEC 2022](https://doi.org/10.2118/210986-MS) (SPE-210986-MS), and ResearchGate. AI safety, state space models, and ML infrastructure.
- **Open to:** AI infrastructure consulting, advisory, and conference speaking (NVIDIA GTC, AI Engineer Summit, Ray Summit, Data+AI Summit, QCon, AWS re:Invent customer stage).
- **Portfolio:** [sailikhith.me](https://sailikhith.me/) | Articles: [sailikhithk.com](https://sailikhithk.com/) | AI-readable: [sailikhith.me/llm.txt](https://sailikhith.me/llm.txt)

## 📄 Research & Publications

### 📚 Book Chapters

| Year | Title | Book | Publisher | Links |
|------|-------|------|-----------|-------|
| 2025 | The Evolution and Rise of State Space Models in AI | *A Case-Based Study of State Space Models in Health Care: The New Transformers* (Ch. 1) | Cambridge Scholars Publishing | [ResearchGate →](https://www.researchgate.net/publication/398300276_The_Evolution_and_Rise_of_State_Space_Models_in_AI) |
| 2025 | Future Trends in AI for Cyberbullying Preventions | *Harnessing Generative AI to Combat Cyberbullying in Industry: Strategies, Solutions, and Ethics* (p. 200) | Cambridge Scholars Publishing | [Google Books →](https://books.google.com/books?hl=en&lr=&id=Tv-PEQAAQBAJ&oi=fnd&pg=PA200&dq=Sai+Likhith+Kanuparthi) · [ResearchGate →](https://www.researchgate.net/publication/400478774_Future_Trends_in_AI_for_Cyberbullying_Preventions) |
| 2025 | Contributing Author | *Harnessing Generative AI to Combat Cyberbullying in Industry: Strategies, Solutions, and Ethics* | Cambridge Scholars Publishing | [Google Books →](https://books.google.com/books?hl=en&lr=&id=Tv-PEQAAQBAJ&oi=fnd&pg=PR5&dq=Sai+Likhith+Kanuparthi) |

### 🔬 IEEE Publications

| Year | Title | Venue | Link |
|------|-------|-------|------|
| 2025 | Role of Artificial Intelligence to address Cyberbullying and Future Scope | IEEE Xplore | [IEEE →](https://ieeexplore.ieee.org/abstract/document/11004721) |

### 🎤 Conference Papers

| Year | Title | Venue | Link |
|------|-------|-------|------|
| 2022 | Full-Stack Machine Learning Development Framework for Energy Industry Applications | SPE Abu Dhabi International Petroleum Exhibition and Conference (ADIPEC) · Paper: SPE-210986-MS | [OnePetro →](https://doi.org/10.2118/210986-MS) |

### 📝 Research Articles

| Year | Title | Publisher | Links |
|------|-------|-----------|-------|
| 2025 | Future Trends in AI for Cyberbullying Preventions | ResearchGate / Stemaway Research | [ResearchGate →](https://www.researchgate.net/publication/400478774_Future_Trends_in_AI_for_Cyberbullying_Preventions) · [PDF →](https://stemaway-discourse.s3.dualstack.us-east-2.amazonaws.com/original/2X/b/b69e629aaf20d516434187dae0aaac429f18f031.pdf) |

## 🔓 Open Source Contributions

Contributing upstream to the LLM tooling I use in production at Airbnb. 8 PRs across 5 repos in August 2026.

| Date | Repo | PR | Title | Status |
|------|------|-----|-------|--------|
| 2026-08-17 | `Shubhamsaboo/awesome-llm-apps` | [#1101](https://github.com/Shubhamsaboo/awesome-llm-apps/pull/1101) | fix: remove deprecated pathlib backport and migrate PyPDF2 to pypdf | **MERGED** |
| 2026-08-18 | `explodinggradients/ragas` | [#2959](https://github.com/vibrantlabsai/ragas/pull/2959) | fix(metrics): ContextPrecision returns exactly 1.0 for perfect ranking | Open |
| 2026-08-15 | `vibrantlabsai/ragas` | [#2954](https://github.com/vibrantlabsai/ragas/pull/2954) | fix: strip deprecated top_p for Anthropic provider in InstructorLLM | Open |
| 2026-08-08 | `langchain-ai/langchain` | [#39351](https://github.com/langchain-ai/langchain/pull/39351) | fix(perplexity): capture num_search_queries in usage_metadata for cost tracking | Closed, reopening |
| 2026-08-07 | `livekit/agents` | [#6754](https://github.com/livekit/agents/pull/6754) | feat(evals): add ReliabilityObserver for external reliability scoring | Open |
| 2026-08 | `BerriAI/litellm` | [#37236](https://github.com/BerriAI/litellm/pull/37236) | fix(batches): bill cancelled/failed batches stamped terminal by a client poll | Open |
| 2026-08 | `BerriAI/litellm` | [#37238](https://github.com/BerriAI/litellm/pull/37238) | fix(guardrails): merge model-level guardrails into litellm_metadata for /v1/messages | Open |
| 2026-08 | `BerriAI/litellm` | [#36981](https://github.com/BerriAI/litellm/pull/36981) | fix(vertex_ai): convert messages to contents in gemini count_tokens | Open |

**Focus areas:** LLM cost tracking, eval metrics, provider compatibility, guardrails. Maps directly to my day job building FacadeDriver (30+ LLM orchestration) and eval harnesses (23+ agent versions, 1,690 ground-truth samples) at Airbnb.

## 🏆 Certifications

<p align="left">
  <img src="https://images.credly.com/images/2d84e428-9078-49b6-a804-13c15383d0de/image.png" height="150" alt="AWS Certified Solutions Architect - Professional" />&nbsp;&nbsp;
  <img src="https://images.credly.com/images/b9feab85-1a43-4f6c-99a5-631b88d5461b/image.png" height="150" alt="AWS Certified Developer - Associate" />&nbsp;&nbsp;
  <img src="https://images.credly.com/images/778bde6c-ad1c-4312-ac33-2fa40d50a147/image.png" height="150" alt="AWS Certified Machine Learning - Specialty" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/komal-30/komal-30/main/Azure%20Data%20Scientist%20Associate%20Badge.png" height="150" alt="Microsoft Certified: Azure Data Scientist Associate (DP-100)" />
</p>

**Also certified in:** AWS Solutions Architect Associate · Google Cloud Professional Data Engineer · Oracle Database 12c Administrator · Oracle Java SE 8 Programmer

## Tech Stack & Skills

### Languages
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,java,ts,bash,cpp" />
  </a>
</p>

### AI/ML Infrastructure & Serving
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,aws,azure,gcp,docker,kubernetes" />
  </a>
</p>
**LLM Serving:** vLLM, TensorRT-LLM, AWS Bedrock, OpenAI, Anthropic Claude, SageMaker | **Orchestration:** LangChain, LangGraph, MCP, FacadeDriver (custom multi-model router) | **Eval:** LangSmith, Braintrust, custom eval harnesses (1,690 ground-truth samples)

### Streaming, Data & Observability
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=kafka,redis,elasticsearch,postgres,grafana,prometheus" />
  </a>
</p>
**Streaming:** Kafka (4M req/min), RabbitMQ, Airflow | **Observability:** OpenTelemetry, Loki, Datadog, Grafana, Prometheus, drift detection | **Warehouses:** Databricks, Spark SQL, Hive/Trino, PostgreSQL, Elasticsearch

### Backend & Platforms
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=fastapi,django,flask,spring,nextjs,nginx,jenkins" />
  </a>
</p>

---

## 🏆 GitHub Status

<div align="center">
  <table border="0" cellpadding="0" cellspacing="0" width="100%">
    <tr>
      <td width="50%" valign="top" align="center">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=sailikhithk&background=00000000&border=30363d&stroke=30363d&ring=38bdf8&fire=f97316&currStreakNum=ffffff&sideNums=ffffff&currStreakLabel=38bdf8&sideLabels=94a3b8&dates=64748b">
          <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=sailikhithk&background=00000000&border=e5e7eb&stroke=e5e7eb&ring=0284c7&fire=f97316&currStreakNum=0f172a&sideNums=0f172a&currStreakLabel=0284c7&sideLabels=4b5563&dates=6b7280">
          <img src="https://streak-stats.demolab.com?user=sailikhithk&background=00000000&border=30363d&stroke=30363d&ring=38bdf8&fire=f97316&currStreakNum=ffffff&sideNums=ffffff&currStreakLabel=38bdf8&sideLabels=94a3b8&dates=64748b" alt="GitHub Streak Stats" width="95%" />
        </picture>
      </td>
      <td width="50%" valign="top" align="center">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=sailikhithk&count_private=true&theme=tokyonight">
          <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=sailikhithk&count_private=true&theme=github">
          <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=sailikhithk&count_private=true&theme=tokyonight" alt="GitHub Stats" width="95%" />
        </picture>
      </td>
    </tr>
    <tr>
      <td colspan="2" align="center" valign="top">
        <br/>
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=sailikhithk&layout=compact&bg_color=00000000&border_color=30363d&title_color=38bdf8&text_color=ffffff">
          <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=sailikhithk&layout=compact&bg_color=00000000&border_color=e5e7eb&title_color=0284c7&text_color=0f172a">
          <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=sailikhithk&layout=compact&bg_color=00000000&border_color=30363d&title_color=38bdf8&text_color=ffffff" alt="Top Languages" width="60%" />
        </picture>
      </td>
    </tr>
  </table>
</div>

---

### 🌐 Find Me Online

**Portfolio**: [sailikhith.me](https://sailikhith.me) · **Blog**: [sailikhithk.com](https://sailikhithk.com) · **AI-readable profile**: [sailikhith.me/llm.txt](https://sailikhith.me/llm.txt)

<p align="left">
<a href="https://sailikhith.me" target="_blank"><img align="center" src="https://img.shields.io/badge/Portfolio-sailikhith.me-18BC9C?style=flat&logo=vercel&logoColor=white" alt="Sai Likhith Kanuparthi Portfolio" /></a>&nbsp;
<a href="https://dev.to/sailikhithk" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/devto.svg" alt="Sai Likhith Kanuparthi on DEV.to" height="30" width="40" /></a>
<a href="https://linkedin.com/in/sailikhithk" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="Sai Likhith Kanuparthi on LinkedIn" height="30" width="40" /></a>
<a href="https://medium.com/@sailikhith" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/medium.svg" alt="Sai Likhith Kanuparthi on Medium" height="30" width="40" /></a>
<a href="https://www.hackerrank.com/sailikhithcse" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="Sai Likhith Kanuparthi on HackerRank" height="30" width="40" /></a>
<a href="https://www.leetcode.com/sailikhith" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="Sai Likhith Kanuparthi on LeetCode" height="30" width="40" /></a>
</p>
