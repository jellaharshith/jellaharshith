<!-- ===================== HERO ===================== -->
<div align="center">

# Hi, I'm Harshith Jella 👋

<a href="https://github.com/jellaharshith">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=00BFFF&center=true&vCenter=true&width=640&lines=AI+Security+%C2%B7+Offensive+Security;Building+human-in-the-loop+AI+security+tools;Model+proposes+%E2%86%92+policy+decides+%E2%86%92+human+approves" alt="Typing SVG" />
</a>

**CS @ Cal State East Bay (May 2027)  · Bug Bounty Hunter · Creating Security using AI for Good!**

![Open to](https://img.shields.io/badge/Open_to-AI_Security_Engineer_·_FDE_Security_Engineer-00BFFF?style=for-the-badge)

</div>

---

<!-- ===================== ABOUT ===================== -->
### 🧑‍💻 About me

I build **AI-powered security tools that stay under human control**: LLM agents that plan pentests, triage SOC alerts and write detections, wrapped in deterministic policy gates, scope enforcement and tamper-evident audit logs.

- 🔐 Focus: **AI security**, **penetration testing**, **DFIR / SOC automation**
- 🐞 Bug bounty on **HackerOne**: 15+ public programs, 10+ reports with CVSS scoring and PoCs
- 🤖 Running local security LLMs (Ollama, Foundation-Sec 8B) and fine-tuning my own
- 🎓 CEH v11 · Executive PG Certification in Cybersecurity & Ethical Hacking, **IIT Roorkee**
- 🌱 VP of **Google Developer Group (GDG) CSUEB** · Treasurer, International Student Organization

---

<!-- ===================== PROJECTS ===================== -->
### 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### 🐍 [Viper](https://github.com/jellaharshith/Viper_Security)
Human-controlled AI copilot for **authorized pentesting and bug bounty**. The LLM proposes, a deterministic policy engine decides, and a human approves every active action.

- Default-deny scope, approval checkpoints, emergency stop
- Tools run on an isolated cloud VM, not on the laptop
- SHA-256 hash-chained audit log + RFC-3161 timestamping
- Validated on OWASP Juice Shop: **0 false-confirmed findings, 0 out-of-scope actions**

`Python` `LangGraph` `Ollama` `RAG` `GCP` `SARIF`

</td>
<td width="50%" valign="top">

#### ⚡ [ASM-AI (SWIFTSEC)](https://github.com/jellaharshith/ASM-AI)
AI red-team automation platform for authorized engagements, from OSINT through exploitation and reporting.

- 10-source RAG knowledge base (MITRE ATT&CK, ExploitDB, Nuclei, HackerOne reports, OWASP)
- 26 probe types · Kali tooling in Docker sandboxes
- Every command gated by Rules of Engagement (scope, technique, time window)
- MITRE-mapped, CVSS-scored findings in SARIF / JSON / Markdown

`Python` `Claude` `ChromaDB` `Docker` `Kali`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🛡️ [AI SOC Lab](https://github.com/jellaharshith/AI-SOC-LAB)
Full SOC simulation in Docker with an **agentic LLM as the analyst** across detection → response.

- Wazuh SIEM + attack range: 3 victims, 6 MITRE-tagged attacks
- LLM triages alerts, hunts threats, writes and deploys Wazuh rules, runs IR
- Prompt-injection-aware: logs treated as untrusted data
- Works with Claude, GPT or a fully local model

`Wazuh` `OpenSearch` `Docker` `Python` `LLM agents`

</td>
<td width="50%" valign="top">

#### 📊 [GRC Risk & Compliance Dashboard](https://github.com/jellaharshith/grc-risk-compliance-dashboard)
Full-stack GRC platform for a fictional healthcare company: the full GRC analyst workflow end to end.

- Asset inventory, risk register with Likelihood × Impact scoring
- Controls mapped to **NIST CSF 2.0** + gap assessment
- Executive report with a 30/60/90-day roadmap
- PostgreSQL with Row-Level Security

`Next.js` `TypeScript` `Supabase` `PostgreSQL` `Recharts`

</td>
</tr>
</table>

### 🔬 Currently working on
- Fine-tuning **Llama-3.1-8B (QLoRA + DPO)** on NVD data into a CVE-analysis model, served locally through Ollama
- Researching how attacker-controlled log fields can manipulate **AI alert-triage pipelines**

---

<!-- ===================== STACK ===================== -->
### 🧰 Tech stack

**AI / LLM**<br>
![Claude](https://img.shields.io/badge/Claude_API-191919?style=flat-square&logo=anthropic&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![RAG](https://img.shields.io/badge/RAG_·_ChromaDB-FF6B6B?style=flat-square)
![QLoRA](https://img.shields.io/badge/QLoRA_·_DPO-8B5CF6?style=flat-square)
![MCP](https://img.shields.io/badge/MCP_servers-0EA5E9?style=flat-square)

**Offensive security**<br>
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=flat-square)
![Nuclei](https://img.shields.io/badge/Nuclei-4F46E5?style=flat-square)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white)
![Amass](https://img.shields.io/badge/Amass_·_Subfinder-374151?style=flat-square)
![OpenVAS](https://img.shields.io/badge/OpenVAS-66C430?style=flat-square)

**Defensive / DFIR**<br>
![Wazuh](https://img.shields.io/badge/Wazuh-3595F9?style=flat-square)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![SIFT](https://img.shields.io/badge/SIFT_Workstation-B91C1C?style=flat-square)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-D32F2F?style=flat-square)
![NIST CSF](https://img.shields.io/badge/NIST_CSF_2.0-1E3A8A?style=flat-square)

**Languages, cloud & dev**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

<!-- ===================== PRINCIPLES ===================== -->
### 🧭 How I build security tools

> **The model never grants permission.** LLMs propose; deterministic code enforces scope; a human approves anything active.
> Every finding traces back to real tool output, and every action lands in an audit log.
> All testing I do is authorized: my own systems, intentionally vulnerable labs, or in-scope bug bounty programs.

---

<!-- ===================== ACTIVITY ===================== -->
### 🐍 Contribution activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jellaharshith/jellaharshith/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jellaharshith/jellaharshith/output/github-contribution-grid-snake.svg" />
  <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/jellaharshith/jellaharshith/output/github-contribution-grid-snake.svg" />
</picture>

---

<div align="center">

**Curious mind. Security mindset. Always shipping.** 🔐

![Profile views](https://komarev.com/ghpvc/?username=jellaharshith&style=flat-square&color=00BFFF&label=profile+views)

</div>
