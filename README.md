<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:7aa2f7,100:bb9af7&height=200&section=header&text=Amir%20Yaghoubi&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=Backend%20Engineer%20%E2%86%92%20AI-First%20Full-Stack%20Builder&descSize=18&descAlignY=58" width="100%" />

<a href="https://github.com/amir-yaghoubi">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=800&color=7AA2F7&center=true&vCenter=true&width=640&lines=Go+%C2%B7+Rust+%C2%B7+Node.js+at+the+core;Distributed+systems+that+don't+lose+money;AI-first%3A+spec+%E2%86%92+agents+%E2%86%92+shipped;Backend+%2B+Frontend+%2B+DevOps%2C+end+to+end" alt="Typing SVG" />
</a>

<p>
  <a href="https://www.linkedin.com/in/amir-yaghoubi-dev/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:amir.yaghoubi.dev@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://t.me/Amirh_Yaghoubi"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" /></a>
  <a href="https://x.com/amir_ina_"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
</p>

</div>

---

### 👋 About me

I'm a **Senior Backend Engineer** with **7+ years** of building high-traffic, fault-tolerant distributed systems, from crypto-exchange infrastructure that moves millions in daily volume to real-time SocialFi platforms.

**Go**, **Rust** and **Node.js** are my home turf. I care about correctness, consistency and observability, not just shipping features.

Today I work **AI-first**. I treat coding agents as a team that I lead: I write the spec, model the domain, record the decisions, and let agents build against tests and golden fixtures. That lets one engineer ship across the **whole stack**: backend, web, mobile, desktop and the infrastructure under it.

```yaml
role:        Senior Backend Engineer → AI-First Full-Stack
core:        [Go, Rust, Node.js / TypeScript]
also_ships:  [Next.js, Angular, Astro, Jetpack Compose, Flutter, egui]
runs_on:     [AWS, Kubernetes, Terraform, Docker, a homelab with too many boxes]
cares_about: [idempotency, exactly-once, observability, boring deploys]
```

---

### 🤖 How I build: AI-first

- **Spec-driven development.** Every non-trivial project starts with a PRD, a domain glossary (`CONTEXT.md`), and ADRs for decisions that are hard to undo. Agents then build against that contract, not against guesses.
- **Agents as a delivery team.** Claude Code and OpenCode work from a local issue tracker with triage labels (`ready-for-agent` / `ready-for-human`), reusable skills, and git worktrees so several features move in parallel.
- **Verification over vibes.** Migrations and rewrites are gated by golden fixtures, live dual-runs against the old system, contract tests, Playwright E2E and k6 load tests.
- **AI inside the product.** I build LLM-powered features, not just LLM-assisted code: autonomous agents with guardrails, human review and rate limits.
- **Local models.** I run Ollama, LM Studio and quantized GGUF models on my own hardware for private and offline workloads.

---

### 🚀 Highlights

- **Re-architected the blockchain deposit/withdrawal core** at a crypto exchange, from a monolith to event-driven microservices (Go + Node.js) with Outbox/Inbox patterns and idempotency keys. Race-condition failures dropped by **99.3%**.
- **Replaced legacy cron jobs** with Kafka + CDC + CQRS pipelines: **14s → 1.1s** end-to-end (12× faster) with exactly-once semantics.
- **Cut operational incidents by 94%** (100+ → under 10 PagerDuty alerts a month) through chaos engineering and automated rollback pipelines.
- **Integrated 15 blockchain networks** (EVM, UTXO, Solana, Cosmos) to expand cross-chain liquidity.
- **Reduced infrastructure costs by up to 55%** through smart caching and cloud-native architecture.
- **Led backend teams**, drove core re-architecture, and built a custom Software Security Module (SSM) for cryptographic operations.
- **Building the backend of a real-time social platform** end to end: content feeds, subscriptions and paywalls, live streaming, and a third-party OAuth API.
- **Leading a full backend rewrite to Rust**, with each endpoint checked against the old system before cutover.
- **Built an autonomous AI agent service** in Go that runs LLM-driven users on a live platform, with guardrails and human review.
- **Replaced paid third-party services** with in-house Go microservices and shipped a real-time WebSocket layer for live updates.
- **Own the cloud platform as code**: Terraform and Helm on AWS (Kubernetes, managed Postgres and Redis, serverless, CDN) across dev, staging and production.

---

### 🧩 What I've been building lately

| Project | What it is | Stack |
|---|---|---|
| **Detoman** | SaaS that helps small sellers price goods and track whether their capital grows in USD / gold terms despite inflation. Multi-tenant, with a web PWA, Android app and landing page | Go · sqlc · OpenTelemetry · Next.js · Kotlin |
| **telesms** | Personal SMS ↔ Telegram gateway on an LTE modem, with a ratatui TUI and an egui desktop client that renders Persian correctly | Rust · SQLite · egui |

---

### 📌 Open source

| Project | Description | Stack |
|---|---|---|
| [telesms-bot](https://github.com/amir-yaghoubi/telesms-bot) | Two-way SMS ↔ Telegram gateway: USB LTE modem via ModemManager, one forum topic per contact | Rust |
| [chapar](https://github.com/amir-yaghoubi/chapar) | Pull-based outbox event publisher for reliable delivery in financial systems | Rust |
| [axum-clean-architecture](https://github.com/amir-yaghoubi/axum-clean-architecture) | Template for a (modified) clean architecture on Axum | Rust |
| [afrasyab](https://github.com/amir-yaghoubi/afrasyab) | Invite-only Telegram bot that saves YouTube, SoundCloud and Telegram files to your Google Drive | Rust |
| [openwrt-tls-frag](https://github.com/amir-yaghoubi/openwrt-tls-frag) | Unblock YouTube and Instagram on OpenWrt by fragmenting the TLS ClientHello: no proxy, no VPN | Shell |
| [freepbx_telegram_voicemail](https://github.com/amir-yaghoubi/freepbx_telegram_voicemail) | Sends FreePBX voicemails to Telegram | Rust |
| [sms-telebot](https://github.com/amir-yaghoubi/sms-telebot) | Android app that forwards SMS, calls and battery alerts to Telegram or email | Dart |
| [vernemq-api](https://github.com/amir-yaghoubi/vernemq-api) | REST APIs around the VerneMQ broker | Go |
| [mqttpattern](https://github.com/amir-yaghoubi/mqttpattern) | MQTT topic pattern matching | Go |
| [remoty](https://github.com/amir-yaghoubi/remoty) | Control your computer remotely from the CLI | Go |
| [utel-fiber-prometheus-exporter](https://github.com/amir-yaghoubi/utel-fiber-prometheus-exporter) | Prometheus exporter for a fiber panel, with Docker + Grafana | Go |
| [drone-navigation-service](https://github.com/amir-yaghoubi/drone-navigation-service) | Clean Architecture + DDD example | Go |

---

### 🛠️ Tech stack

<p align="center"><b>Backend</b><br/>
  <img src="https://skillicons.dev/icons?i=go,rust,nodejs,ts,nestjs,elixir,python&theme=dark" />
</p>
<p align="center"><b>Frontend · Mobile</b><br/>
  <img src="https://skillicons.dev/icons?i=nextjs,react,angular,astro,tailwind,kotlin,flutter&theme=dark" />
</p>
<p align="center"><b>Data · Messaging</b><br/>
  <img src="https://skillicons.dev/icons?i=postgres,redis,mongodb,mysql,sqlite,kafka,rabbitmq,prisma&theme=dark" />
</p>
<p align="center"><b>Cloud · DevOps · Observability</b><br/>
  <img src="https://skillicons.dev/icons?i=aws,kubernetes,terraform,docker,cloudflare,linux,bash,prometheus,grafana&theme=dark" />
</p>

```
Patterns:      Event-Driven · CQRS · Outbox/Inbox · CDC · DDD · Hexagonal · Microservices
Messaging:     Kafka · NATS · RabbitMQ · MQTT · SQS / EventBridge · BullMQ
Observability: Datadog · OpenTelemetry · Prometheus · Grafana
Testing:       Golden fixtures · Dual-run diffing · Playwright · Vitest · k6
AI tooling:    Claude Code · OpenCode · agent skills · Ollama · LM Studio · LLM APIs
```

---

### 📊 GitHub stats

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=amir-yaghoubi&theme=tokyonight" width="100%" />
  <img height="170em" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=amir-yaghoubi&theme=tokyonight" />
  <img height="170em" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=amir-yaghoubi&theme=tokyonight" />
</div>

---

<div align="center">

**Open to senior / staff-level Backend, Platform & AI-first Full-Stack roles: remote-first.**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:bb9af7,50:7aa2f7,100:1a1b27&height=100&section=footer" width="100%" />

</div>
