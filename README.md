<p align="right">
  <a href="https://github.com/Eurobotics-Association/Cyber-Mike/blob/main/README-fr.md">🇫🇷 Version Française</a>
</p>

# Cyber-Mike – Project Overview

**Cyber-Mike** is an intelligent cybersecurity agent designed for **non-specialists** — families, shop owners, small and medium businesses (SMEs), and associations. It provides clear, actionable insights about networks and devices, leveraging proven open-source cybersecurity tools.

---

## 🌟 Goals

- **Cyber Support for the Vulnerable** – Assist individuals and organizations with limited cybersecurity skills.
- **Provide a Multimodal AI Interface** – Install, configure, and operate complex cybersecurity tools, delivering clear reports and advice through voice, Telegram, and email.
- **Simplify and Develop Cyber Awareness** – Translate complex concepts and strengthen user understanding.
- **Empower Without Overwhelming** – Allow experts to handle complexity while informing users.
- **Offer Preventive Support** – Deliver alerts and advice before incidents occur.

>

---

## 🤖 What is Cyber-Mike?

Cyber-Mike is an expert agent connected to:

- `ntopng` for network visibility
- `Wazuh` for host security
- `Suricata` for intrusion detection
- `CrowdSec` for collaborative reputation
- Orchestrated via `n8n`

It communicates through:

- ChatGPT / OpenAI Operator / MCP
- Web interface, email, Telegram

Cyber-Mike provides:

- Accessible explanations of cyber threats
- Automated reports and dashboards
- Escalation recommendations (e.g., "contact a professional")

Cyber-Mike does **not** replace enterprise cybersecurity teams but acts as a **bridge** for daily support and can also assist technology enthusiasts and advanced users in improving their cybersecurity practices.

---

## ⚙️ Architecture & Technical Spirit

- Open-source back-end tools
- Front-end tools: multimodal relational AI agent (voice, text, email via Telegram, ChatGPT, etc.)
- Real-time orchestration via `n8n`
- LLM integration (OpenAI, with local fallback)
- Option for decentralized hosting via FluxOS
- Docker-based auto-installation with AI-guided configuration for easy user setup
- Easy deployment for non-IT users, individuals, associations, SMEs
- Physical deployment possible via Raspberry Pi Ethernet/PoE dongle
- Emergency local mode without Internet connection
- Mass-deployable by ISPs or telecom operators to protect their residential subscribers

Cyber-Mike is *not*:

- A miracle solution
- A GRC tool
- A forensic investigation kit
- An integrated antivirus solution
- A cybersecurity engineer

Cyber-Mike is:

- An intelligent intermediary
- A friendly cyber analyst for households, shops, and small structures
- A knowledge and decision-support assistant
- An intelligent interface between users and cybersecurity tools
- A tool providing the minimum necessary detailed elements to a professional to assist users

---

## 🔒 Privacy & Sovereignty

- Local operation by default – **no data exfiltration**
- Cloud backup and expert escalation – **GDPR-compliant and opt-in only**
- Priority given to privacy and open-source interoperability
- Option to run a self-hosted local AI

---

## 🚀 Relevance for Companies

**Cyber-Mike is an affordable cybersecurity intelligence layer designed to scale across millions of vulnerable users.**

Deployable by ISPs and telecom operators seeking to:

- Offer advanced protection directly managed by their subscribers
- Standardize alerts and analyses
- Reduce compromise risks among residential subscribers
- Decrease malware and botnet propagation
- Improve regulatory NIS2 compliance for ISPs and operators

---

## 🤝 Project Support

Project supported by **Eurobotics**, non-profit association under French Law 1901 – [contact@eurobotics.org](mailto:contact@eurobotics.org)  
**Eurobotics**, Association Loi 1901, RNA W603008100, Compiègne, France
