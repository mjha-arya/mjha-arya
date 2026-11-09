<h1 align="center">Manish Jha</h1>
<h3 align="center">I build AI agents that are <i>secure</i> and <i>provable</i>, not just impressive in a demo.</h3>

<p align="center">
  10 years in security operations (KPMG · Okta · enterprise financial services) · London<br/>
  <b>Upwork Top Rated · 90% Job Success</b> · CEH · Microsoft Azure Security Engineer
</p>

<p align="center">
  <a href="https://www.upwork.com/freelancers/~014e778cd52bd8d530"><img src="https://img.shields.io/badge/Hire_me-Upwork-14a800?style=for-the-badge&logo=upwork&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/jhakumarmanish"><img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

<p align="center"><b>▶ <a href="https://mjha-arya.github.io/agent-swarm/">Try the live voice-agent demo</a></b>, with the safety gates checking it on screen</p>

---

### What I do

Most AI agents ship as a prompt and a hope. I spent a decade in SecOps learning that **an agent that's confidently wrong is worse than no agent**, because it manufactures false assurance. So everything I build is:

- 🔐 **Least-privilege.** *The harness holds the privilege, not the agent.* Read-only by default, with writes gated by a human.
- 🧪 **Proven by evals.** Golden cases, including adversarial ones, exist *before* the model is chosen.
- 🧾 **Honest about what it did.** Tool-call traces over self-reporting. Every report ends with **NOT CHECKED**.

### Products

| | What it does |
|---|---|
| 🔱 **[Shiva](https://github.com/mjha-arya/shiva)** | Plain-English requirement → least-privilege AI agent → **Proof Report**. The Kartikeya gate (*Blast Radius × Capability Delta*) quarantines undeclared credential access and data egress *inline* |
| 🏁 **[Pit Box](https://github.com/mjha-arya/pitbox)** | A multi-agent verdict engine for Microsoft estates. Predicts from architecture, verifies with fetched citations, and an adversarial reviewer can force a re-think. Minutes instead of a 5–10 week support case |
| 🧱 **[Databricks Control Tool](https://github.com/mjha-arya/dct-overview)** | Detect → safe fix with rollback → auditor-grade evidence for Databricks, as one closed loop |

### Open-source agents

| Repo | Highlights |
|---|---|
| 🧹 **[agent-lint](https://github.com/mjha-arya/agent-lint)** | **New.** A least-privilege and supply-chain linter for Claude Code agents, skills and MCP servers. Catches unpinned MCP servers, `Bash(*)`, bypassed permissions and plaintext tokens. Zero dependencies, SARIF output, GitHub Action |
| 🛡️ **[DOC-foundry](https://github.com/mjha-arya/DOC-foundry)** | Adversarial detection engineering. Blue writes Sigma rules, Red attacks them, and a deterministic referee proves coverage |
| 🕵️ **[secops-agents](https://github.com/mjha-arya/secops-agents)** | Claude Agent SDK agents for Defender XDR investigation, read-only MCP servers, a PM → architect → dev agent team, and **an agent that audits agents** |
| 🐝 **[agent-swarm](https://github.com/mjha-arya/agent-swarm)** | The G0–G5 gate ladder every agent passes before shipping, plus a **[live voice-agent demo](https://mjha-arya.github.io/agent-swarm/)** with gates on screen |
| 📊 **[peerbench](https://github.com/mjha-arya/peerbench)** | LangGraph: P&L CSV → cited competitor benchmark. Every number is traced to a source. 5/5 golden, including CSV prompt-injection |
| 🎙️ **[agentchirp](https://github.com/mjha-arya/agentchirp)** | The last 24h of AI-engineering posts on X → a timed voice briefing on Telegram. Read-only, idempotent, 60+ tests |
| 📜 **[constitution-of-agents](https://github.com/mjha-arya/constitution-of-agents)** | The seven articles every agent I build inherits |

### Security architecture

[Threat Modelling](https://github.com/mjha-arya/Threat-Modelling) · [Threat Model for Vuln Management](https://github.com/mjha-arya/Threat-Model-for-Vulnerability-Management) · [DLP Blueprint](https://github.com/mjha-arya/DLP-Framework-Blueprint) · [Honeypot Blueprint](https://github.com/mjha-arya/Honeypot-deployment-Blueprint) · [Intune Cloud Attach](https://github.com/mjha-arya/intune-cloud-attach-architecture) · [Threat Hunting Library](https://github.com/mjha-arya/threat-hunting-framework)

### Stack

**Agents:** Claude Agent SDK · Claude Code · LangGraph · MCP · pydantic · Gemini · evals and LLM-as-judge<br/>
**Security:** Microsoft Defender XDR · Sentinel · Purview (DLP) · Entra ID · Intune · Splunk · threat hunting · IR<br/>
**Cloud & data:** Azure · AWS · Databricks (Unity Catalog) · IaC · Python · PowerShell

### Work with me

- **Agent security review:** least-privilege scoping, red-teaming, and an eval suite for an agent you already have
- **Build a governed agent:** from brief to golden evals to a production agent with an audit trail
- **SecOps automation:** Microsoft security stack, detection engineering, incident response

👉 **[Start on Upwork](https://www.upwork.com/freelancers/~014e778cd52bd8d530)** or **[message me on LinkedIn](https://www.linkedin.com/in/jhakumarmanish)**.
