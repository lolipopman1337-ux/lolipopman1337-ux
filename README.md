<h1 align="center">AI Automation Engineer</h1>

<p align="center">
  <em>Production AI pipelines • Multi-agent orchestration • Operational reliability</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/n8n-EA4B71?logo=n8ndotio&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Anthropic-191919?logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Telegram%20Bot%20API-26A5E4?logo=telegram&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white" />
</p>

---

I build production AI/automation systems — n8n + LLM pipelines, multi-agent Telegram bots, voice-to-content workflows, and the operational glue that keeps them alive (health-checks, error routing, audit trails). Two years shipping for B2B clients in real estate / SMB automation.

I treat reliability as a feature: every pipeline has explicit fallbacks, an audit row in Postgres, and a dead-man-switch monitor — because silent failure is the worst failure mode.

---

### Featured

- **[n8n-automation-templates](https://github.com/lolipopman1337-ux/n8n-automation-templates)** — production-tested templates, including a 6-workflow multi-agent orchestrator (capture → LLM router → 4 specialised sub-agents). Patterns: structured-output routing, `executeWorkflow` chaining, single-row audit trail, dead-man-switch monitoring.
- *More public projects coming — currently extracting and sanitising from a 60+ workflow production stack.*

---

### What I work on

- **Multi-agent orchestration** — splitting one mega-prompt into small routed agents, each with its own audit and prompt
- **Voice-first pipelines** — Telegram voice → Whisper / Deepgram → LLM rewrite → channel post
- **Lead qualification** — BANT scoring, structured-output JSON, Postgres chat memory
- **Operational reliability** — global error routing, health-check workflows, monitor-of-monitors, graceful degradation
- **VPS hardening** — Docker non-root, secret rotation, iptables, systemd discipline

### Stack

- **Orchestration:** n8n (self-hosted, 60+ workflows in prod)
- **LLM:** OpenAI (`gpt-4o`, `whisper-1`), Anthropic (`claude-sonnet`, `claude-haiku`), LangChain
- **Persistence:** Supabase / Postgres, schema design, REST via PAT
- **Surface:** Telegram Bot API + Telethon, webhooks, callback routing
- **Infra:** Docker, systemd, journalctl, VPS (Contabo / Hetzner), Cisco NDG Linux Essentials + Cybersecurity Essentials
- **Adjacent (commercial 3D background):** AVEVA E3D, Tekla, Navisworks — 2.5 years industrial design before pivoting to automation

---

### Currently

Open to AI / automation engineering roles (remote / EU / GMT+7 friendly). Strongest fit: companies turning manual SOPs into AI-augmented workflows.

Reach out via GitHub or open an issue on any of the repos.
