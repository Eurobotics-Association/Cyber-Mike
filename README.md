# Cyber-Mike – Project Overview

**Cyber-Mike** is an AI-driven cybersecurity support agent designed for **non-specialists** — from families and small shop owners to small-and-medium-sized enterprises (SMEs) and associations. It provides understandable, actionable insights into networks and devices using real-time data from trusted open-source cybersecurity tools.

---

## 🌟 Goals

- **Cyber Support for the Vulnerable** – Help people and organizations with no cybersecurity background.
- **Make Cyber Easy** – Translate complex concepts into human-readable language.
- **Empower, Don’t Overwhelm** – Let experts handle complexity while users stay informed.
- **Provide Preemptive Guidance** – Give alerts and advice before incidents occur.
- **Build Cyber Literacy** – Educate users with natural language reports and learning tools.

---

## 🤖 What is Cyber-Mike?

Cyber-Mike is an expert AI agent connected to:
- `ntopng` for network visibility  
- `Wazuh` for host-based security  
- `Suricata` for intrusion detection  
- `CrowdSec` for community-driven reputation  
- Orchestrated using `n8n`

It communicates via:
- ChatGPT / OpenAI Operator / MCP  
- Web UI, Email, Telegram

Cyber-Mike provides:
- Human-friendly explanations of cyber threats
- Automated reports and dashboards
- Escalation recommendations (e.g. “call a pro”)

It does **not** replace enterprise cybersecurity teams or certifications, but serves as a **bridge** for daily support.

---

## ⚙️ Tech Stack & Spirit

- Open-source backend tools (ntopng, suricata, etc...)
- Front-end tools: multimodal relational AI agent (voice, text, email via Telegram, ChatGPT, etc.)
- Real-time orchestration via `n8n`
- LLM integration (OpenAI, local fallback)
- Optional decentralized hosting via FluxOS
- Docker-based auto-install setup
- Local-only fallback mode for offline operation
- Designed for telecom-scale deployment (e.g., in routers)

Cyber-Mike is *not*:
- A silver bullet  
- A GRC tool  
- A forensics toolkit

Cyber-Mike *is*:
- A smart intermediary  
- A friendly AI analyst for homes, shops, and small orgs  
- A knowledge assistant

---

## 🔒 Privacy & Sovereignty

- Runs locally by default – **no data exfiltration**
- Optional cloud backup & expert escalation – **GDPR-compliant & opt-in**
- Privacy-first, open-source compatible
- Self-hosted AI support possible

---

## 🚀 Enterprise Readiness

**Cyber-Mike is a low-cost cybersecurity intelligence layer scalable to millions of users.**

Designed for ISPs, telcos, and MSSPs to:
- Embed into routers or user devices
- Standardize insights across clients
- Improve NIS2 compliance
- Reduce client-side breach risks


