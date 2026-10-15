<div align="center">
  <img src="https://github.com/user-attachments/assets/1bc1d554-3c63-40e6-a1c6-2261843ff601" width="100%" alt="Raj Bharti" />
  <img src="https://github.com/user-attachments/assets/2c35c80b-ceab-4f07-a3d9-df7c9aec791d" width="100%" alt="ARISE" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Cinzel&weight=700&size=30&duration=3000&pause=1000&color=7B5EA7&center=true&vCenter=true&width=900&height=70&lines=Raj+Bharti;AI+%26+Cybersecurity+Engineer;Autonomous+SOC+%C2%B7+Offline+LLMs+%C2%B7+Identity+Security" />
</div>

<div align="center">
  <a href="https://rajbharti.in"><img src="https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=firefox&logoColor=7B5EA7" /></a>
  <a href="https://www.linkedin.com/in/rajbharti-in"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=38BDF8" /></a>
  <a href="https://orcid.org/0009-0000-8162-7611"><img src="https://img.shields.io/badge/ORCID-0d1117?style=for-the-badge&logo=orcid&logoColor=A6CE39" /></a>
  <a href="https://x.com/RajBharti06"><img src="https://img.shields.io/badge/X-0d1117?style=for-the-badge&logo=x&logoColor=c9d6e3" /></a>
</div>

<br/>

<div align="center">
  <b>Cybersecurity undergrad at RIT Croatia, Zagreb.</b><br/>
  I build security and AI systems that run without sending your data anywhere,<br/>
  and publish open research on how identity attacks actually succeed.
</div>

<img src="https://github.com/user-attachments/assets/d6bca50b-ed39-4860-bb0b-77b5aea24998" width="100%" alt="" />

## ⛓️ Philosophy

```python
class RajBharti:
    role     = ["AI & Cybersecurity Engineer", "Independent Researcher", "Builder"]
    location = "Zagreb, Croatia"
    focus    = "identity security · offline inference · multi-agent systems"

    def principles(self) -> list:
        return [
            "run offline, zero data leaves the device",
            "privacy by design, not as an afterthought",
            "publish open research anyone can read",
            "ship it, then prove it works",
        ]

    def current(self) -> str:
        return "ARGUS · FirellySAT · The Orchestrator"
```

<img src="https://github.com/user-attachments/assets/d6bca50b-ed39-4860-bb0b-77b5aea24998" width="100%" alt="" />

## 🔬 Research

<div align="center">

| Paper | Venue | Status |
|:---|:---|:---:|
| **The Identity Exploitation Model** · quantifying compound breach risk in AiTM phishing campaigns | Computers & Security (Elsevier) | 🔄 Under review |
| [The Harvard University Data Breach: Identity-Centric Threats and the Failure of MFA](https://zenodo.org/records/19344102) | Zenodo | 📄 Open access |
| [Princeton University Data Breach and Its Cybersecurity Implications in Higher Education](https://zenodo.org/records/19136388) | Zenodo | 📄 Open access |

</div>

> **The Identity Exploitation Model (IEM)** is a four-layer sequential framework that treats a breach as a chain rather than a set of independent failures. It computes end-to-end probability across Human Trust, Authentication, Interception and Privilege. Monte Carlo simulation over five documented university breaches puts FIDO2 migration at a 72% reduction in breach probability, against 15% for awareness training alone. Grounded in MITRE ATT&CK and STRIDE. ORCID [0009-0000-8162-7611](https://orcid.org/0009-0000-8162-7611).

<img src="https://github.com/user-attachments/assets/d6bca50b-ed39-4860-bb0b-77b5aea24998" width="100%" alt="" />

## ⚙️ What I Build

<table>
<tr>
<td width="50%" valign="top">

### 🛡️ ARGUS &nbsp;[→](https://github.com/Rajbharti06/ARGUS)
**Autonomous Cyber Defense Platform**

Seven-module SOC dashboard. VEIL for phishing triage on Qwen3.6-35B-A3B, ORACLE for attack correlation on NVIDIA Nemotron 49B, IDENTITY for behavioral trust scoring.

Live CVE and CISA KEV feeds, real host telemetry. No mock data anywhere in production endpoints.

`Python` `FastAPI` `React 18` `WebSockets`

</td>
<td width="50%" valign="top">

### 🤖 My Mitra &nbsp;[→](https://github.com/Rajbharti06/My-Mitra)
**Privacy-First Offline AI Companion**

100% on-device LLM inference at roughly 120ms latency on mid-range Android. Habits, journaling, routines, all stored locally.

Zero exfiltration by architecture, not by policy. Nothing is ever transmitted.

`Python` `FastAPI` `Ollama` `Mistral`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔒 ClaimGuard Vision &nbsp;[→](https://github.com/Rajbharti06/ClaimGuard-Vision)
**Evidence-Based Claims Verification**

Verifies insurance and delivery damage claims from images and conversation history. Deterministic guardrails override model hallucinations with hard business rules.

Hardened against prompt injection hidden in images, with watermark detection to catch stock-photo fraud.

`Python` `Vision LLMs` `Multi-Provider Failover`

</td>
<td width="50%" valign="top">

### 📊 HireFlow AI &nbsp;[→](https://github.com/Rajbharti06/hireflow-ai)
**AI Resume Screener** · `AGPL-3.0`

Three-signal hybrid scoring: sentence embeddings, skill-graph overlap, LLM reasoning. Ranks 100+ resumes in seconds with plain-English explanations.

Zero-Cost Mode runs fully offline on a local model. No API key needed.

`Python` `Streamlit` `Supabase`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 The Orchestrator &nbsp;[→](https://github.com/Rajbharti06/The-Orchestrator)
**Multi-Agent Deployment Pipeline**

One prompt to a deployed application in five stages: intent parsing, task decomposition, code generation, verification, deployment.

Provider-agnostic LLM routing with automatic bug fixing. Ships to Vercel, Railway or Render.

`Python` `Multi-Agent LLMs`

</td>
<td width="50%" valign="top">

### 🩺 PulseLock AI &nbsp;[→](https://github.com/Rajbharti06/PulseLock-AI)
**Always-On Access Firewall**

Intercepts every request touching patient data, whether it comes from a human, a service or an AI agent, and makes a real-time allow or deny decision before execution.

`JavaScript` `Zero Trust`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎤 IntervAI &nbsp;[→](https://github.com/Rajbharti06/IntervAI)
**AI Interview Simulator**

Real-time Whisper ASR under 2s latency. Detects hesitation, interrupts rambling, adapts tone to the interviewer personality you pick.

Most people don't enjoy using it. That's the point.

`Python` `Whisper` `Streamlit`

</td>
<td width="50%" valign="top">

### 📚 FirellySAT &nbsp;[→](https://firelly.in)
**AI-Powered SAT Prep**

Adaptive practice, LLM-generated study plans, progress analytics. Calm Mode adds breathing exercises and a distraction-free interface.

Most prep platforms optimize for pressure. This one doesn't.

`Next.js 15` `TypeScript` `Vercel`

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>

<br/>

| Project | What it does |
|:---|:---|
| [**SafeRoute**](https://github.com/Rajbharti06/SafeRoute) | Trust-aware AI support triage. Corpus-grounded routing with risk-aware escalation, self-verification and prompt-injection defense. 276th globally in HackerRank Orchestrate. |
| [**SANJAYA Edge**](https://github.com/Rajbharti06/SANJAYA-EDGE) | AI road-safety copilot. Computer vision plus traffic-law context for real-time violation detection and multilingual alerts. |
| [**LoanDoc Guardian**](https://github.com/Rajbharti06/LoanDoc-Guardian) | AI risk intelligence for syndicated loan documentation review. |
| [**Jarvis Coder**](https://github.com/Rajbharti06/Jarvis-Coder) | Offline AI coding assistant. Monaco Editor and FastAPI with local inference, no GPU, no cloud. |
| [**DRIFT**](https://github.com/Rajbharti06/DRIFT) | Daily cooperative word game on Reddit. Ten players relay a secret word through 3-word clues. The full chain reveals at midnight. |

</details>

<img src="https://github.com/user-attachments/assets/d6bca50b-ed39-4860-bb0b-77b5aea24998" width="100%" alt="" />

## 🧰 Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,typescript,go,c,react,nextjs,fastapi,flutter,docker,linux,postgres,supabase&theme=dark" />
</p>

```
AI / ML     Ollama · Mistral · Qwen3 · Whisper ASR · HuggingFace · LangChain · RAG · FAISS
Security    MITRE ATT&CK · STRIDE · Threat Modeling · Zero Trust · OSINT · Prompt-Injection Defense
Infra       Docker · Cloudflare R2 · Vercel · Railway · Render · WebSockets
```

<img src="https://github.com/user-attachments/assets/d6bca50b-ed39-4860-bb0b-77b5aea24998" width="100%" alt="" />

## 📈 Activity

<div align="center">

  ![Stars](https://img.shields.io/github/stars/Rajbharti06?style=for-the-badge&logo=github&color=7B5EA7&labelColor=0d1117&label=Total+Stars)
  ![Followers](https://img.shields.io/github/followers/Rajbharti06?style=for-the-badge&logo=github&color=38BDF8&labelColor=0d1117&label=Followers)

</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Rajbharti06&bg_color=0d1117&color=38BDF8&line=7B5EA7&point=ffffff&hide_border=true&area=true&area_color=7B5EA7&custom_title=Contribution+Graph" width="95%" />
</div>

<img src="https://github.com/user-attachments/assets/d6bca50b-ed39-4860-bb0b-77b5aea24998" width="100%" alt="" />

<div align="center">
  <h3>Build systems. Publish research. Ship things that matter.</h3>
  <a href="https://rajbharti.in"><b>rajbharti.in</b></a>
  <br/><br/>
  <i>Portfolio · Publications · Full project list</i>
</div>
