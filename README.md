# Hi, I'm Ignacio 👋

**Site Reliability / Platform / Software Engineer with 12+ years running critical production systems.**

> 🟢 **Open to work: SRE / Platform / Software Engineer, remote or Santiago**, available immediately.

I build and run production platforms end to end: cloud infrastructure, Kubernetes, IaC, CI/CD, observability, and the services on top of them. I've worked on AWS since 2019 and have led single-region to multi-region migrations in production. I hold 11 CNCF certifications.

### Featured projects

| Project | Stack | What it does |
|---|---|---|
| [orderflow](https://github.com/ipenas-cl/orderflow) | Go · NATS JetStream · PostgreSQL · Stripe · Auth0 · React/TS · OpenTelemetry · Helm · Terraform | An e-commerce order, payment and fulfillment platform built like production: five hexagonal services, a saga with compensations, a transactional outbox and an idempotent inbox, and a circuit breaker, retries with jitter, bulkheads, rate limits and idempotency keys. It includes a Stripe adapter with verified webhooks, an Auth0/JWT backoffice with RBAC and an audit log, Grafana SLOs and burn-rate alerts, and chaos scripts that show the saga compensating. |
| [hookrelay](https://github.com/ipenas-cl/hookrelay) | Rust · axum · tokio · SQLite | A reliable webhook relay. It verifies HMAC `X-Hub-Signature-256` signatures (WhatsApp/Meta style), persists events to a durable queue, and delivers them with retries, exponential backoff, a dead-letter queue, idempotency keys and Prometheus metrics. |
| [slo-probe](https://github.com/ipenas-cl/slo-probe) | Go · Prometheus | A synthetic prober that computes SLIs, error budgets and multi-window burn-rate alerts. It exports metrics, and its CLI report can serve as a deploy gate. |
| [hookrelay-console](https://github.com/ipenas-cl/hookrelay-console) | TypeScript · React · Vite | An operator UI for hookrelay with deliveries, the dead-letter queue, one-click replay and a mock mode. |
| [pasito](https://github.com/ipenas-cl/pasito) | TypeScript · React · Vite · PWA · IndexedDB | An offline-first learning app for kids aged 2–7 that teaches speaking, numbers and reading (Spanish phonics). It uses the Web Speech API for text-to-speech and speech recognition, spaced repetition and adaptive difficulty, and has a parent dashboard with streaks. The domain is hexagonal and tested, with Playwright and axe e2e tests. No ads, no tracking. |
| [kernel-patch-validator](https://github.com/ipenas-cl/kernel-patch-validator) | Shell | Checks Linux kernel patches before you submit them upstream. I announced it on linux-kernel-mentees, where Greg Kroah-Hartman reviewed it ("I like the idea") and suggested moving the checks into `checkpatch.pl`, which I then proposed as checkpatch patches. |
| [Chronos](https://github.com/ipenas-cl/Chronos) | C · x86-64 Assembly | An experimental systems language designed to be deterministic and memory-safe. Its compiler, written in C and Assembly, emits native ELF64 binaries with no libc. |
| [AtomicOS](https://github.com/ipenas-cl/AtomicOS) | Assembly | An operating system written from scratch in Assembly. |
| [leafwise](https://github.com/ipenas-cl/leafwise) | Go · PyTorch · ONNX Runtime · React PWA · Postgres · MinIO | A smart gardening assistant. It schedules watering and feeding from a soil water balance driven by real Open-Meteo weather, and diagnoses leaf diseases from photos with a MobileNetV3 I fine-tuned on PlantVillage (94% test accuracy), served through ONNX Runtime behind a hexagonal diagnosis port with an optional vision-LLM second opinion. |

### Experience highlights

- **Linux kernel (2025):** got cleanup patches accepted into Linux staging by Greg Kroah-Hartman.
- **Gauss Control (2026):** owned a multi-tenant IoT platform on GKE end to end, with Kafka, Redis, BigQuery, Terraform Cloud, Python and Go, at USD 50K+ a month in cloud spend.
- **Macal, Head of Operations (2021–2025):** built the SRE team from scratch and took AWS from single-region to multi-region. Cut infrastructure costs by 40% and reached 99.9% availability.
- **COPEC (2019–2021):** migrated 200+ applications to AWS, shipped 13 deploys a day with zero downtime, and ran them multi-region on Aurora Global Database, RDS cross-region replicas, DynamoDB Global Tables and CDC, with Route 53 failover and regular disaster-recovery drills.
- **Itaú, Practia (2011–2019):** built QA automation for banking and enterprise systems.

### Toolbox

- **Languages:** Go, Rust, TypeScript, Python, Shell
- **Cloud:** AWS (multi-region, Route 53, Global Accelerator, EKS/ECS, Aurora, RDS, DynamoDB), GCP (GKE, BigQuery), Cloudflare
- **Platform:** Kubernetes, Docker, Kafka, Redis, Argo CD
- **IaC and CI/CD:** Terraform, CloudFormation, GitHub Actions, GitLab CI, Jenkins
- **Data:** PostgreSQL, MySQL, SQL Server, DB2, MongoDB, Redis
- **Observability:** Prometheus, Grafana, OpenTelemetry, New Relic, CloudWatch
- **Certifications:** 11 CNCF certifications, MBA

### Contact

LinkedIn: https://www.linkedin.com/in/ignacio-pe%C3%B1a-2905b454/

Native Spanish speaker, professional working proficiency in English.

## Certifications

**11 Linux Foundation / CNCF certifications:** CKAD · KCNA · KCSA · PCA (Prometheus) · OTCA (OpenTelemetry) · CAPA (Argo) · CGOA (GitOps) · CNPA (Platform Engineering) · CBA (Backstage) · KCA (Kyverno) · CCA (Cilium)
