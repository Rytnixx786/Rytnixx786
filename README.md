<div align="center">

<!-- HERO BANNER (Uses ./assets/banner.svg in Rytnixx786/Rytnixx786) -->
<p>
  <a href="https://mehedi-hasan-llm.vercel.app/">
    <img src="./assets/banner.svg" width="100%" alt="Mehedi Hasan — AI & Backend Systems Engineer" />
  </a>
</p>

<!-- ANIMATED TERMINAL TELEMETRY -->
<p>
  <a href="https://mehedi-hasan-llm.vercel.app/">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=15&duration=3000&pause=1100&color=10B981&center=true&vCenter=true&width=780&height=28&lines=I+build+the+deterministic+systems+around+stochastic+AI+models.;10.86x+vLLM+Serving+Speedup+(331+tok%2Fs)+%C2%B7+4.12ms+Semantic+Cache;Stateful+LangGraph+Agents+%C2%B7+Hybrid+BM25%2FDense+RAG+%C2%B7+NLI+Refusal+Gates;CI%2FCD+Model+Promotion+Gates+%C2%B7+Offline-First+SQLite+WAL+Sync" alt="Mehedi Hasan — Systems & AI Engineering" />
  </a>
</p>

<!-- NAVIGATION & VERIFIED CONTACT LINKS -->
<p>
  <a href="https://mehedi-hasan-llm.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-mehedi--hasan--llm.vercel.app-10b981?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0d1117" alt="Portfolio" /></a>&nbsp;
  <a href="https://www.linkedin.com/in/mehedi-hasan-llm"><img src="https://img.shields.io/badge/LinkedIn-mehedi--hasan--llm-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117" alt="LinkedIn" /></a>&nbsp;
  <a href="https://github.com/Rytnixx786"><img src="https://img.shields.io/badge/GitHub-Rytnixx786-10b981?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117" alt="GitHub" /></a>&nbsp;
  <a href="mailto:nafismehedi37@gmail.com"><img src="https://img.shields.io/badge/Email-nafismehedi37%40gmail.com-0f766e?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117" alt="Email" /></a>
</p>

</div>

---

### `01 // ENGINEERING THESIS & SYSTEM PROFILE`

> **"I care about what happens *after* the model responds."**  
> A language model is only one component of a production system. Real reliability comes from the infrastructure around it: adaptive admission control, hybrid retrieval with calibrated refusal gates, durable state checkpointing, idempotent CI/CD evaluation harnesses, and tamper-evident security boundaries.

<table>
  <tr>
    <td width="54%" valign="top">
      <h4>Core Architectural Focus</h4>
      <ul>
        <li><b>Inference Control & Serving:</b> Self-hosted quantized LLM serving (<code>vLLM</code>, <code>AWQ Marlin INT4</code>), PID concurrency regulation, semantic vector caching, and FinOps token cutoffs.</li>
        <li><b>Evidence-First Retrieval:</b> Hybrid <code>BM25</code> + dense vector search with Reciprocal Rank Fusion (<code>k = 60</code>), cross-encoder reranking, and NLI entailment refusal gates.</li>
        <li><b>Durable Agent Orchestration:</b> Cyclic <code>LangGraph</code> workflows backed by PostgreSQL state checkpointing, human-in-the-loop approval gates, and resumable SSE replay.</li>
        <li><b>Zero-Trust & Offline-First Sync:</b> Multi-tenant PostgreSQL Row-Level Security (RLS), chained <code>SHA-256</code> audit ledgers, and SQLite WAL outbox sync for disconnected environments.</li>
      </ul>
    </td>
    <td width="46%" valign="top">
      <h4>System Diagnostics</h4>
<pre lang="yaml"><code>engineer: "Mehedi Hasan"
location: "Dhaka, Bangladesh (UTC+6)"
education: "B.Sc. in CSE @ BRAC University"
experience:
  - "SWE Intern @ FlyRank (Metering & Billing)"
  - "Independent AI & Backend Systems Builder"
principles:
  - "Evidence first — refuse when proof is missing"
  - "Show the engineering, don't decorate it"
  - "Every model promotion requires a CI gate"</code></pre>
    </td>
  </tr>
</table>

---

### `02 // FLAGSHIP PRODUCTION SYSTEMS`

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/Rytnixx786/Cinch">Cinch</a> — LLM Gateway & Serving</h3>
      <p>14-stage async FastAPI inference gateway & <code>AWQ Marlin INT4</code> serving control plane for <code>Qwen2.5-7B</code> on 8 GB VRAM GPUs with PID admission control, Kubernetes HPA, and FinOps token cutoffs.</p>
      <ul>
        <li><b>10.86×</b> throughput speedup (<b>331 tok/s</b>) & <b>4.87×</b> lower TTFT</li>
        <li><b>4.12 ms</b> semantic cache hits & <b>45 ms</b> circuit-breaker fast-fail</li>
        <li><b>195</b> deterministic CI tests + EBNF/AST JSON grammar repair</li>
      </ul>
      <p>
        <a href="https://github.com/Rytnixx786/Cinch"><code>Source ↗</code></a> ·
        <a href="https://mehedi-hasan-llm.vercel.app/work/cinch"><code>Case Study ↗</code></a> ·
        <code>Python</code> <code>FastAPI</code> <code>vLLM</code> <code>K8s</code> <code>Prometheus</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🕸️ <a href="https://github.com/Rytnixx786/Nexus">Nexus Researcher</a> — Agentic Workflow</h3>
      <p>Deterministic 8-node <code>LangGraph</code> deep-research engine with 4-stage hybrid retrieval, human-in-the-loop approval gates, PostgreSQL checkpointing, and resumable SSE streaming.</p>
      <ul>
        <li><b>8.05 req/s</b> sustained load with durable PostgreSQL state recovery</li>
        <li><b>91%</b> adversarial refusal accuracy on sparse/conflicting evidence</li>
        <li><b>122</b> backend test suites passing with Redis token-bucket rate limits</li>
      </ul>
      <p>
        <a href="https://github.com/Rytnixx786/Nexus"><code>Source ↗</code></a> ·
        <a href="https://mehedi-hasan-llm.vercel.app/work/nexus-researcher"><code>Case Study ↗</code></a> ·
        <code>LangGraph</code> <code>FastAPI</code> <code>pgvector</code> <code>Redis</code> <code>React</code>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/Rytnixx786/Ares">ARES</a> — MLOps Promotion Gate</h3>
      <p>Idempotent model reliability, drift detection, and regression-gating platform evaluating candidate builds against golden sets and live champions directly in CI/CD.</p>
      <ul>
        <li><b>92%+</b> enforced test coverage across <b>72</b> test modules (<code>~420</code> tests)</li>
        <li>Configurable F1, latency, KS/PSI drift, and demographic slice gates</li>
        <li>Async SQLAlchemy + PostgreSQL decision trail, Celery workers & Streamlit UI</li>
      </ul>
      <p>
        <a href="https://github.com/Rytnixx786/Ares"><code>Source ↗</code></a> ·
        <a href="https://mehedi-hasan-llm.vercel.app/work/ares"><code>Case Study ↗</code></a> ·
        <code>Python</code> <code>FastAPI</code> <code>SQLAlchemy</code> <code>DVC</code> <code>MLflow</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🧠 <a href="https://github.com/Rytnixx786/MindStack">MindStack</a> — Calibrated Hybrid RAG</h3>
      <p>Evidence-first retrieval platform combining sparse lexical matching (<code>BM25</code>) and dense embeddings (<code>ChromaDB</code>) with cross-encoder reranking to eliminate ungrounded synthesis.</p>
      <ul>
        <li><b>95%</b> QA groundedness via Reciprocal Rank Fusion (<code>k = 60</code>)</li>
        <li>Boosted adversarial refusal accuracy from <b>26.7% → 66.7%</b></li>
        <li>Parent-child document chunking + pre-generation NLI entailment gate</li>
      </ul>
      <p>
        <a href="https://github.com/Rytnixx786/MindStack"><code>Source ↗</code></a> ·
        <a href="https://mehedi-hasan-llm.vercel.app/work/mindstack"><code>Case Study ↗</code></a> ·
        <code>FastAPI</code> <code>ChromaDB</code> <code>BM25</code> <code>Ragas</code> <code>React</code>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🔒 <a href="https://github.com/Rytnixx786/OFF-Boarder">OFFBoarder</a> — Zero-Trust SaaS</h3>
      <p>Multi-tenant enterprise offboarding platform automating access revocation with strict database-level tenant isolation, Risk Radar telemetry, and tamper-evident audit ledgers.</p>
      <ul>
        <li>PostgreSQL RLS session isolation + Segregation of Duties (<code>Creator ≠ Approver</code>)</li>
        <li>Chained <b>SHA-256</b> cryptographic audit logs & transactional outbox retries</li>
        <li>Real-time revocation workflows across identity, cloud, and hardware assets</li>
      </ul>
      <p>
        <a href="https://github.com/Rytnixx786/OFF-Boarder"><code>Source ↗</code></a> ·
        <a href="https://mehedi-hasan-llm.vercel.app/work/offboarder"><code>Case Study ↗</code></a> ·
        <code>Next.js 16</code> <code>TypeScript</code> <code>Prisma</code> <code>Supabase RLS</code>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🩺 <a href="https://github.com/DigontaDas/MaSheba--AI">MaSheba AI</a> — Offline-First Clinical Sync</h3>
      <p>Bangla maternal healthcare & on-device risk triage platform engineered for rural community health workers operating in zero-connectivity zones.</p>
      <ul>
        <li>Local SQLite WAL outbox queue with microsecond logical-clock conflict resolution</li>
        <li>On-device <code>ONNX</code> risk scoring, resumable media sync & Bangla voice RAG</li>
        <li>3-portal ecosystem: Expo mobile app, FastAPI backend, and PostGIS admin map</li>
      </ul>
      <p>
        <a href="https://github.com/DigontaDas/MaSheba--AI"><code>Source ↗</code></a> ·
        <a href="https://mehedi-hasan-llm.vercel.app/work/masheba-ai"><code>Case Study ↗</code></a> ·
        <a href="https://masheba-docs.vercel.app/docs"><code>Docs ↗</code></a> ·
        <code>Expo</code> <code>ONNX</code> <code>FastAPI</code> <code>PostGIS</code>
      </p>
    </td>
  </tr>
</table>

---

### `03 // ADDITIONAL SYSTEMS, INFRASTRUCTURE & RESEARCH`

| System / Repository | Architectural Domain | Key Engineering Highlights | Stack |
| :--- | :--- | :--- | :--- |
| **[flyrank-capstone-metering-billing](https://github.com/Rytnixx786/flyrank-capstone-metering-billing)** | Multi-Tenant Usage Metering & Stripe Billing | Idempotent usage event ingestion, tiered pricing calculation engine, and asynchronous Stripe webhook state reconciliation. | `FastAPI` `SQLAlchemy 2` `Stripe SDK` `Pydantic v2` |
| **[celloscope-assessment](https://github.com/Rytnixx786/celloscope-assessment)** | Clinical Speech & Lab Report Extraction | Strict 3-layer clean architecture (`api` / `services` / `adapters`), deterministic zero-credential mock mode, and `25` contract & layer-isolation tests. | `Python 3.11` `FastAPI` `Pydantic v2` `Docker` `Pytest` |
| **[autonomous-security-ai](https://github.com/Rytnixx786/autonomous-security-ai)** | Self-Learning Cyber-Defense Agent | Streaming telemetry anomaly detection with adaptive policy enforcement and human analyst feedback recalibration loop. | `Python` `scikit-learn` `Typer CLI` `Pydantic` |
| **[my-portfolio-website](https://github.com/Rytnixx786/my-portfolio-website)** | Interactive Engineering Portfolio & Case Studies | Deep-dive system architecture case studies, interactive architecture graph inspector, and Gemini-backed system query route. | `Next.js 16` `React 19` `TypeScript 5` `Tailwind 4` |
| **Clinical 3D CCTA & OS Kernel Work** | Volumetric Medical AI & Low-Level Systems | **3D CCTA Coronary Stenosis Engine** (`RASNet` + `SegResNet`, **95.2%** adjacent CAD-RADS agreement), **SimpleFS** (custom C file system with superblocks & inode tables), and a **RISC-V `xv6` Lottery Scheduler**. | `PyTorch 3D` `C` `POSIX` `RISC-V xv6` |

---

### `04 // REFERENCE ARCHITECTURE & MEASURED BENCHMARKS`

How my production AI pipelines enforce deterministic quality, latency, and safety boundaries before streaming a single token to the client:

```mermaid
flowchart LR
    A["Client Ingress"] --> B{"PII Guardrail &\nPID Rate Gate"}
    B -->|"Cache Hit (4.12 ms)"| C["Semantic Vector Cache"]
    B -->|"Cache Miss"| D["Hybrid Retrieval\n(BM25 + Dense Vector)"]
    D --> E["RRF Merger (k=60)\n+ Cross-Encoder Rerank"]
    E --> F{"NLI Entailment Gate\n(Score >= 0.85)"}
    F -->|"Verified Evidence"| G["vLLM Marlin INT4 /\nLangGraph StateGraph"]
    F -->|"Insufficient Proof"| H["Calibrated Refusal /\nQuery Re-Planner"]
    G --> I["Cited SSE Stream +\nSHA-256 Audit Ledger"]
```

<details>
<summary><b>📊 View Verified Engineering Benchmark Summary (Click to Expand)</b></summary>
<br />

| System | Evaluated Metric | Baseline / Unoptimized | Engineered Result | Verification Context |
| :--- | :--- | :--- | :--- | :--- |
| **[Cinch](https://github.com/Rytnixx786/Cinch)** | Generation Throughput & TTFT | `30.48 tok/s` (`FP16` baseline) | **`331.0 tok/s` (`10.86×`) · `4.87×` lower TTFT** | `Qwen2.5-7B-Instruct` AWQ Marlin INT4 on 8 GB VRAM GPU + `195` CI tests |
| **[Cinch](https://github.com/Rytnixx786/Cinch)** | Cache Hit & Fast-Fail Latency | Full LLM round-trip (`>1,200 ms`) | **`4.12 ms` cache hit · `45 ms` breaker trip** | Redis semantic cache + sliding-window circuit breaker |
| **[Nexus Researcher](https://github.com/Rytnixx786/Nexus)** | Adversarial Refusal & Load | Unchecked single-pass RAG | **`91%` refusal accuracy · `8.05 req/s` load** | 8-node LangGraph + PostgreSQL checkpointing + `122` backend tests |
| **[MindStack](https://github.com/Rytnixx786/MindStack)** | Groundedness & Refusal Rate | `26.7%` refusal on unanswerable queries | **`95%` groundedness · `66.7%` refusal accuracy** | Hybrid BM25 + ChromaDB (`RRF k=60`) + NLI pre-generation gate |
| **[ARES](https://github.com/Rytnixx786/Ares)** | Automated Regression Gate Coverage | Ad-hoc notebook checks | **`92%+` enforced coverage (`~420` tests)** | 7 GitHub Actions workflows + unit, integration, contract & property tests |

</details>

---

### `05 // PRODUCTION STACK BY ARCHITECTURAL LAYER`

<div align="center">
  <p>
    <img src="https://skillicons.dev/icons?i=py,ts,js,c,bash,pytorch,fastapi,nodejs,nextjs,react,tailwind,postgres,redis,mongodb,sqlite,supabase,prisma,docker,kubernetes,githubactions,vercel,linux&perline=11" alt="Core Production Stack" />
  </p>
</div>

<table>
  <tr>
    <td width="28%"><b>Languages & Systems</b></td>
    <td width="72%">
      <img src="https://img.shields.io/badge/Python_3.11%2B-0f172a?style=flat-square&logo=python&logoColor=38bdf8" alt="Python" />
      <img src="https://img.shields.io/badge/TypeScript_5-0f172a?style=flat-square&logo=typescript&logoColor=3178c6" alt="TypeScript" />
      <img src="https://img.shields.io/badge/JavaScript-0f172a?style=flat-square&logo=javascript&logoColor=f7df1e" alt="JavaScript" />
      <img src="https://img.shields.io/badge/C_(POSIX_%2F_xv6)-0f172a?style=flat-square&logo=c&logoColor=a8b9cc" alt="C" />
      <img src="https://img.shields.io/badge/SQL-0f172a?style=flat-square&logo=postgresql&logoColor=38bdf8" alt="SQL" />
      <img src="https://img.shields.io/badge/Bash-0f172a?style=flat-square&logo=gnubash&logoColor=10b981" alt="Bash" />
    </td>
  </tr>
  <tr>
    <td><b>LLM Serving, RAG & ML</b></td>
    <td>
      <img src="https://img.shields.io/badge/vLLM_%26_Marlin_INT4-0f172a?style=flat-square&logo=nvidia&logoColor=10b981" alt="vLLM" />
      <img src="https://img.shields.io/badge/LangGraph_StateGraph-0f172a?style=flat-square&logo=chainlink&logoColor=38bdf8" alt="LangGraph" />
      <img src="https://img.shields.io/badge/Hybrid_RAG_(BM25_%2B_RRF)-0f172a?style=flat-square&logo=databricks&logoColor=f59e0b" alt="Hybrid RAG" />
      <img src="https://img.shields.io/badge/PyTorch_%26_ONNX_Runtime-0f172a?style=flat-square&logo=pytorch&logoColor=ee4c2c" alt="PyTorch & ONNX" />
      <img src="https://img.shields.io/badge/Ragas_%26_Evidently_Evals-0f172a?style=flat-square&logo=huggingface&logoColor=ffd21e" alt="Evals" />
    </td>
  </tr>
  <tr>
    <td><b>Backend & Distributed APIs</b></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI_(Async_%2B_SSE)-0f172a?style=flat-square&logo=fastapi&logoColor=009688" alt="FastAPI" />
      <img src="https://img.shields.io/badge/Async_SQLAlchemy_2.0-0f172a?style=flat-square&logo=sqlalchemy&logoColor=ef4444" alt="SQLAlchemy" />
      <img src="https://img.shields.io/badge/Pydantic_v2-0f172a?style=flat-square&logo=pydantic&logoColor=e92063" alt="Pydantic" />
      <img src="https://img.shields.io/badge/Celery_%26_Redis_Queues-0f172a?style=flat-square&logo=celery&logoColor=37814a" alt="Celery" />
      <img src="https://img.shields.io/badge/Node.js_%26_Prisma-0f172a?style=flat-square&logo=prisma&logoColor=38bdf8" alt="Node & Prisma" />
    </td>
  </tr>
  <tr>
    <td><b>Data, Vector & Edge Storage</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL_16_(pgvector_%2B_RLS)-0f172a?style=flat-square&logo=postgresql&logoColor=4169e1" alt="PostgreSQL" />
      <img src="https://img.shields.io/badge/ChromaDB-0f172a?style=flat-square&logo=airbyte&logoColor=f97316" alt="ChromaDB" />
      <img src="https://img.shields.io/badge/Redis_7-0f172a?style=flat-square&logo=redis&logoColor=dc2626" alt="Redis" />
      <img src="https://img.shields.io/badge/SQLite_WAL_(Offline_Sync)-0f172a?style=flat-square&logo=sqlite&logoColor=38bdf8" alt="SQLite" />
      <img src="https://img.shields.io/badge/Supabase_%26_PostGIS-0f172a?style=flat-square&logo=supabase&logoColor=3ecf8e" alt="Supabase" />
    </td>
  </tr>
  <tr>
    <td><b>Frontend & Mobile Surfaces</b></td>
    <td>
      <img src="https://img.shields.io/badge/Next.js_16_(App_Router)-0f172a?style=flat-square&logo=nextdotjs&logoColor=ffffff" alt="Next.js" />
      <img src="https://img.shields.io/badge/React_19-0f172a?style=flat-square&logo=react&logoColor=61dafb" alt="React" />
      <img src="https://img.shields.io/badge/React_Native_%26_Expo-0f172a?style=flat-square&logo=expo&logoColor=ffffff" alt="Expo" />
      <img src="https://img.shields.io/badge/Tailwind_CSS_v4-0f172a?style=flat-square&logo=tailwindcss&logoColor=06b6d4" alt="Tailwind CSS" />
      <img src="https://img.shields.io/badge/Streamlit-0f172a?style=flat-square&logo=streamlit&logoColor=ff4b4b" alt="Streamlit" />
    </td>
  </tr>
  <tr>
    <td><b>MLOps, Cloud & Observability</b></td>
    <td>
      <img src="https://img.shields.io/badge/Docker_%26_Compose-0f172a?style=flat-square&logo=docker&logoColor=2496ed" alt="Docker" />
      <img src="https://img.shields.io/badge/Kubernetes_(k3d_%2B_HPA)-0f172a?style=flat-square&logo=kubernetes&logoColor=326ce5" alt="Kubernetes" />
      <img src="https://img.shields.io/badge/GitHub_Actions_CI%2FCD-0f172a?style=flat-square&logo=githubactions&logoColor=2088ff" alt="GitHub Actions" />
      <img src="https://img.shields.io/badge/Prometheus_%26_OpenTelemetry-0f172a?style=flat-square&logo=prometheus&logoColor=e6522c" alt="Prometheus & OTel" />
      <img src="https://img.shields.io/badge/DVC_%26_MLflow-0f172a?style=flat-square&logo=mlflow&logoColor=0194e2" alt="DVC & MLflow" />
    </td>
  </tr>
</table>

---

### `06 // TELEMETRY & ACTIVITY`

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api?username=Rytnixx786&show_icons=true&hide_border=true&bg_color=0d1117&title_color=10b981&icon_color=10b981&text_color=c9d1d9" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api?username=Rytnixx786&show_icons=true&hide_border=true&bg_color=ffffff&title_color=0f766e&icon_color=10b981&text_color=1f2937" />
    <img height="165" src="https://github-stats-extended.vercel.app/api?username=Rytnixx786&show_icons=true&hide_border=true&bg_color=0d1117&title_color=10b981&icon_color=10b981&text_color=c9d1d9" alt="GitHub Stats for Rytnixx786" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Rytnixx786&hide_border=true&background=0D1117&ring=10B981&fire=10B981&currStreakLabel=10B981&sideLabels=C9D1D9&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=8B949E" />
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=Rytnixx786&hide_border=true&background=FFFFFF&ring=0F766E&fire=10B981&currStreakLabel=0F766E&sideLabels=1F2937&currStreakNum=0F172A&sideNums=0F172A&dates=6B7280" />
    <img height="165" src="https://streak-stats.demolab.com?user=Rytnixx786&hide_border=true&background=0D1117&ring=10B981&fire=10B981&currStreakLabel=10B981&sideLabels=C9D1D9&currStreakNum=FFFFFF&sid=FFFFFF&dates=8B949E" alt="GitHub Streak for Rytnixx786" />
  </picture>
</div>

---

<div align="center">
  <sub>Built with deterministic systems discipline · <a href="https://mehedi-hasan-llm.vercel.app/"><b>mehedi-hasan-llm.vercel.app</b></a> · <a href="mailto:nafismehedi37@gmail.com"><b>nafismehedi37@gmail.com</b></a></sub>
</div>
