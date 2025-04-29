<p align="right">
  <a href="https://github.com/Eurobotics-Association/Cyber-Mike/blob/main/README.md">🇬🇧 English Version</a>
</p>

# Cyber-Mike – Présentation du Projet

**Cyber-Mike** est un agent de cybersécurité intelligent, conçu pour les **non-spécialistes** — familles, commerçants, petites et moyennes entreprises (PME) et associations. Il fournit des informations claires et exploitables sur les réseaux et les équipements, en s'appuyant sur des outils open-source de cybersécurité reconnus.

---

## 🌟 Objectifs

- **Soutien Cyber pour les Vulnérables** – Aider les personnes et structures sans compétences en cybersécurité.
- **Fournir une Interface IA Multimodale** – Installer, paramétrer et exploiter des outils cyber complexes, et restituer aux utilisateurs des rapports et conseils clairs via la voix, Telegram, email.
- **Simplifier et Développer la Culture Cyber** – Traduire les concepts complexes et renforcer la compréhension des utilisateurs.
- **Autonomiser sans Submerger** – Laisser les experts traiter la complexité, tout en informant les utilisateurs.
- **Offrir un Soutien Préventif** – Donner des alertes et des conseils avant les incidents.

>

---

## 🤖 Qu'est-ce que Cyber-Mike ?

Cyber-Mike est un agent expert connecté à :

- `ntopng` pour la visibilité réseau
- `Wazuh` pour la sécurité des hôtes
- `Suricata` pour la détection d'intrusions
- `CrowdSec` pour la réputation collaborative
- Orchestré via `n8n` / `LangChain` 

Il communique via :

- ChatGPT / OpenAI Operator / MCP / autres Chats
- Interface web, e-mail, Telegram

Cyber-Mike fournit :

- Des explications accessibles sur les menaces cyber
- Des rapports automatisés et tableaux de bord
- Des recommandations d'escalade (ex : "contacter un professionnel")

Cyber-Mike ne remplace **pas** les équipes de cybersécurité d'entreprise, mais sert de **pont** pour un soutien quotidien, et peut également **accompagner** les **passionnés** de technologie et **utilisateurs avancés** dans leur démarche de sécurisation.
---

## ⚙️ Architecture & Esprit Technique

- Outils back-end open-source
- Outils front-end : agent IA relationnel multimodal (voix, texte, email via Telegram, ChatGPT, etc.)
- Orchestration en temps réel via `n8n`
- Intégration LLM (OpenAI, fallback local)
- Option d'hébergement décentralisé via FluxOS
- Installation automatique via Docker avec paramétrage guidé par IA pour simplifier la configuration utilisateur
- Mode local d'urgence sans connexion Internet
- Déployable massivement par les FAI, opérateurs télécoms ou MSSP pour protéger leurs clients

Cyber-Mike n'est *pas* :

- Une solution miracle
- Un outil GRC
- Un kit d'investigation judiciaire

Cyber-Mike est :

- Un intermédiaire intelligent
- Un analyste cyber amical pour foyers, commerces, petites structures
- Un assistant de connaissance

---

## 🔒 Respect de la Vie Privée & Souveraineté

- Fonctionnement local par défaut – **aucune exfiltration de données**
- Sauvegarde cloud et escalade vers experts – **respect du RGPD et sur opt-in**
- Priorité à la confidentialité et à l'interopérabilité open-source
- Support possible d'une IA auto-hébergée

---

## 🚀 Pertinence pour les Entreprises

**Cyber-Mike est une couche d'intelligence cyber abordable, conçue pour s'étendre à des millions d'utilisateurs vulnérables.**

Déployable par les FAI, opérateurs télécoms et MSSP souhaitant :

- Offrir une protection avancée directement chez leurs clients
- Standardiser les alertes et analyses
- Améliorer la conformité NIS2
- Réduire les risques de compromission chez les clients

---

## 🤝 Soutien du Projet

Projet soutenu par **Eurobotics**, association loi 1901 – [contact@eurobotics.org](mailto:contact@eurobotics.org)  
**Eurobotics**, Association Loi 1901, RNA W603008100, Compiègne, France

