# Security Mastery Console

An **offline, single-file** interactive learning platform covering the advanced domains a senior security professional needs — built for both **certification prep** and **real-world implementation**.

Open [`security-mastery-console.html`](security-mastery-console.html) in any browser. No server, no build step, no internet required. Progress is saved locally in your browser.

## What's inside

**16 domains · 166 topics**, each expanding into a comprehensive lesson:

| # | Domain | # | Domain |
|---|--------|---|--------|
| 01 | Threat Modeling & Secure Design | 09 | Offensive Security & Red Teaming |
| 02 | Application Security | 10 | Reverse Engineering & Malware Analysis |
| 03 | API & Web Security | 11 | Detection, Blue Team & Threat Hunting |
| 04 | Cloud Security | 12 | Incident Response & Digital Forensics |
| 05 | Container & Kubernetes Security | 13 | Cyber Threat Intelligence |
| 06 | DevSecOps & Supply-Chain Security | 14 | Governance, Risk & Compliance |
| 07 | Cryptography & PKI | 15 | *(AI / ML & LLM Security)* |
| 08 | Identity, Access & Zero Trust | 16 | AI / ML & LLM Security |

Each topic includes, where applicable:

- **How it works** — the underlying mechanism / protocol / internals in depth
- **Attack techniques** — with real MITRE ATT&CK technique IDs and CVE examples
- **Defenses & implementation** — the exact controls, configs, and tools to ship
- **Detection & monitoring** — concrete log sources, rules, and signals
- **Real-world example** — a specific incident/CVE and its lesson
- **Certification exam focus** — what CKS / OSCP / CISSP / GCIH / etc. actually test
- Reference **tables**, multiple **code/config examples**, **pitfalls**, a **checklist**, and hand-drawn **diagrams**

## Features

- **Progress tracking** — tick topics as you master them; a mastery meter tracks all 166 topics (saved to `localStorage`)
- **Certification roadmap** — 8 career tracks / 30 certs (entry → core → advanced → expert), with a "my focus" filter
- **Search & level filters** across every topic, tool, and standard
- **Live links** to canonical standards (OWASP, NIST, MITRE, CIS, RFCs) and tools
- **Export to Markdown** (Notion-ready, checkbox state preserved) and **Print / PDF**

## Run it offline

**Simplest:** double-click [`open-security-console.command`](open-security-console.command) (macOS), or just open the HTML file in a browser.

**Local server (optional):**
```bash
python3 -m http.server 8080
# then visit http://localhost:8080/security-mastery-console.html
```

The app is 100% offline. The outbound reference links (docs, videos, labs) naturally require internet only when you click them.

## Disclaimer

Educational material for **authorized, defensive, and certification-study use only**.

---
*Built with [Claude Code](https://claude.com/claude-code).*
