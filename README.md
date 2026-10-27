<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1d4ed8,100:06b6d4&height=200&section=header&text=Adam%20Nguyen&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Backend%20%C2%B7%20Distributed%20Systems%20%C2%B7%20Cloud%20Infrastructure&descAlignY=60&descSize=18" alt="Adam Nguyen - Backend, Distributed Systems, Cloud Infrastructure" />

<a href="https://github.com/nguyenadamq"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=38BDF8&center=true&vCenter=true&width=640&lines=Software+Engineer+I+%40+Project+vNext;I+build+reliable+event-driven+backends;Go+%C2%B7+Python+%C2%B7+TypeScript+%C2%B7+AWS;Oregon+State+CS+%2726" alt="Typing animation" /></a>

<br/>

<a href="https://www.linkedin.com/in/adam-q-nguyen"><img src="https://img.shields.io/badge/LinkedIn-adam--q--nguyen-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:nguyenadamq@gmail.com"><img src="https://img.shields.io/badge/Email-nguyenadamq@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<img src="https://img.shields.io/badge/Based_in-Oregon-0f172a?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Oregon" />

</div>

---

## 👋 About

I'm a **backend-focused software engineer** who likes the unglamorous parts of systems that make them trustworthy: retries, idempotency, backpressure, observability, and schemas that don't break the people who depend on them.

I just finished my **B.S. in Computer Science at Oregon State University** and now work on the backend of a mobile app that reaches **over a million users**. Outside of work I build self-hosted tools for the things I'd otherwise do by hand: tracking jobs, scheduling my week, and answering questions over documents.

```go
type Adam struct {
    Role     string   // Software Engineer I, Project vNext
    Focus    []string // event-driven backends, APIs, cloud infrastructure
    Daily    []string // Go, Python, TypeScript, PostgreSQL, AWS, Terraform
    Exploring []string // retrieval + LLM tooling, Swift/SwiftUI
    Values   string   // boring, observable, well-tested systems
}
```

---

## 💼 Experience

<table>
<tr>
<td width="170" valign="top"><b>Jul 2026 – Present</b></td>
<td>

**Software Engineer I** · Project vNext *(Remote)*<br/>
A new platform rolling out inside an existing mobile app used by **1M+ people**.

- Designed event-driven workflows on **AWS** (EventBridge, SQS, PostgreSQL, S3) with retries, dead-letter queues, replay and idempotent processing
- Wrote reusable **Terraform/OpenTofu** modules with KMS encryption, least-privilege IAM, retention, versioning, TLS enforcement and automated validation
- Evolved **Protocol Buffer / ConnectRPC** contracts across backend and Android while keeping them backward compatible; hardened APIs with error redaction
- Built **Go** services and middleware, including per-platform minimum app-version enforcement, and a support-chat handoff feature
- Improved **PostgreSQL** scalability and integrity: partitioned tables, reversible migrations, UUID idempotency keys, tests against real databases

<sub><code>Go</code> <code>PostgreSQL</code> <code>AWS</code> <code>Terraform</code> <code>gRPC</code> <code>ConnectRPC</code> <code>Protobuf</code> <code>Kotlin</code> <code>GitHub Actions</code></sub>

</td>
</tr>
<tr>
<td valign="top"><b>Feb – Jul 2026</b></td>
<td>

**Information Systems Technician** · Oregon State University<br/>
Built an internal documentation Q&A server: **97% answer accuracy, ~9s average query time.**

- Hybrid retrieval: **SQLite FTS5/BM25 + LanceDB vectors + Ollama embeddings + ONNX cross-encoder reranking**
- File-watching ingestion that re-indexes PDF/DOCX as they change; everything containerized with Docker Compose

<sub><code>Node.js</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>Redis</code> <code>Docker</code> <code>RAG</code></sub>

</td>
</tr>
<tr>
<td valign="top"><b>Sep 2025 – Jun 2026</b></td>
<td>

**Software Engineer (Volunteer Platform)** · In Time of Need<br/>
An AI-assisted pipeline that finds and classifies community resources for staff review.

- Cut resource discovery time by **60%** across **500+ websites**; improved dataset precision by **40%** over 300+ verified resources
- OpenAI + Brave Search + Playwright pipeline feeding a React/Node review UI

<sub><code>TypeScript</code> <code>React</code> <code>Node.js</code> <code>Playwright</code> <code>OpenAI API</code></sub>

</td>
</tr>
<tr>
<td valign="top"><b>Jun – Dec 2025</b></td>
<td>

**Software Engineering Intern** · Qorvo<br/>
Cut manual approval time by **35%** with an Appian workflow for multi-stage supply-chain routing, and migrated a legacy PHP monolith to it with a staged rollout.

<sub><code>Appian</code> <code>SQL</code> <code>PHP</code></sub>

</td>
</tr>
</table>

---

## 🚀 Projects

<table>
<tr>
<td width="50%" valign="top">

### 🛰️ [Job Board Monitor](https://github.com/nguyenadamq/job-board-monitor)
A self-hosted job intelligence platform tracking **5,400+ active sources** across **7 ATS providers**.

- Async polling plane: AsyncIO, provider-isolated queues, 20 workers
- Distributed scheduling with Postgres row leases and Redis token buckets
- Prometheus + Grafana for success/429 rates, p95 latency, retries
- Local Codex/Claude pipeline drafts tailored applications into a **human-reviewed queue**, never auto-submitted

<sub><code>Python</code> <code>FastAPI</code> <code>PostgreSQL</code> <code>Redis</code> <code>Docker</code> <code>Grafana</code></sub>

</td>
<td width="50%" valign="top">

### 🗂️ [My Project Manager](https://github.com/nguyenadamq/my-project-manager)
A private, mobile-first command center for local Git repos, running supervised **Claude (plan/review) + Codex (implement)** pipelines on isolated worktrees.

<sub><code>TypeScript</code> <code>Git worktrees</code> <code>LLM tooling</code></sub>

</td>
</tr>
<tr>
<td valign="top">

### 📅 [Task Pilot](https://github.com/nguyenadamq/task-pilot)
Turns tasks, sleep, work windows and blocked time into an optimized **7-day calendar**.

- Deterministic scheduling engine covered by nine scenarios
- Supabase Auth + Postgres row-level security + Express REST API

<sub><code>React</code> <code>Node.js</code> <code>Supabase</code> <code>Vite</code></sub>

</td>
<td valign="top">

### 🛡️ FlowGuard
End-to-end network anomaly detection on NSL-KDD: PySpark features, scikit-learn Random Forest, served by a validated **FastAPI** endpoint on a two-replica **Kubernetes** deployment.

<sub><code>PySpark</code> <code>scikit-learn</code> <code>Docker</code> <code>Kubernetes</code></sub>

</td>
</tr>
</table>

<sub>More public work: [TennisChallengePal](https://github.com/nguyenadamq/TennisChallengePal) · [Federal Document Intelligence Assistant](https://github.com/nguyenadamq/federal-document-intelligence-assistance) · [Corvallis Housing Bot](https://github.com/nguyenadamq/Corvallis-Housing-Bot-Public). Much of my other work lives in private repos.</sub>

---

## 🧰 Tech stack

<div align="center">

**Languages**<br/>
<img src="https://skillicons.dev/icons?i=go,py,ts,js,swift,cpp,c,bash&theme=dark" alt="Languages" />

**Backend & data**<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,postgres,redis,sqlite,supabase&theme=dark" alt="Backend and data" />

**Cloud & DevOps**<br/>
<img src="https://skillicons.dev/icons?i=aws,terraform,docker,kubernetes,githubactions,prometheus,grafana,linux&theme=dark" alt="Cloud and DevOps" />

**Frontend & tooling**<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind,git,github,playwright&theme=dark" alt="Frontend and tooling" />

</div>

<details>
<summary><b>Everything else I work with</b></summary>

<br/>

| | |
|---|---|
| **Backend** | gRPC, ConnectRPC, REST, Protovalidate, CEL, sqlc, pgx, asyncpg, httpx |
| **Search & AI** | SQLite FTS5/BM25, LanceDB, OpenSearch, Ollama, ONNX Runtime, embeddings, cross-encoder reranking, OpenAI API |
| **AWS** | EventBridge, SQS, S3, CloudWatch, IAM, KMS, LocalStack |
| **Infra** | OpenTofu, Docker Compose, systemd, Oracle Cloud |
| **Mobile** | SwiftUI, Swift concurrency, Kotlin (client integration) |

</details>

---

## 🎯 Currently

- 🔧 Building event-driven backends and cloud infrastructure at Project vNext
- 🛰️ Growing my job-intelligence platform and its observability
- 📚 Going deeper on distributed systems, retrieval, and Swift
- 🤝 Open to talking about backend, infrastructure, and platform engineering roles

<div align="center">

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:1d4ed8,100:0f172a&height=100&section=footer" alt="" />

</div>
