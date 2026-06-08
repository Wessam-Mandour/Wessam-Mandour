<h1 align="center">Wessam Mandour</h1>
<p align="center"><b>AI Automations Expert &amp; Technical Writer</b></p>
<p align="center">I build AI workflows and automations that turn manual processes which once took weeks into runs that finish in seconds, minutes, or at most a couple of hours, reserving AI for the steps that genuinely need it and handling the rest with fast deterministic logic.</p>

<p align="center">
  <a href="https://wessam-mandour.github.io/"><img src="https://img.shields.io/badge/View_my_portfolio-0d1117?style=for-the-badge&logo=githubpages&logoColor=5eead4" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/wessam-mandour/"><img src="https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:wessam.mandour94@gmail.com"><img src="https://img.shields.io/badge/Email-161b22?style=for-the-badge&logo=gmail&logoColor=5eead4" alt="Email"></a>
</p>

---

### 🛠️ Featured: AI Recruiting Automation Platform

An end-to-end platform that takes a job opening from an intake form and runs the entire top-of-funnel automatically: candidate outreach, screening-interview ingestion and scoring, CV parsing, and **LLM-based role matching**, writing a ranked, *explained* shortlist back to the team's workspace. It is **two completely independent projects**, each its own codebase and deployment:

- **Project 01: Role Matching** (Python / FastAPI): a six-stage funnel that ranks candidates with a written rationale each. A run scans **~40,000 rows** and scores **20,000+ of them** (20,000+ LLM API calls) in **90 to 120 minutes** on Railway, posting **Slack status updates** to the whole team.
- **Project 02: Candidate Flow** (Node / Express, 14 services): a mix of **webhook-triggered** automations (CV parsing, transcript fetch + scoring) and **cron-scheduled** reminder sweeps. Sends **2,000+ WhatsApp messages and emails a day** (Twilio + Postmark); CV parser finishes in **under a minute**; a completed interview updates Notion in about **60 seconds**.
- **AI only where it earns its keep:** ~90% of the work runs on DeepSeek where reasoning is needed; parsing, filtering, and routing run on regex and deterministic logic, so no tokens are wasted.
- **One codebase, many deployments:** behavior is driven entirely by environment variables, so the same service ships to each client's needs by config and a redeploy (e.g. DeepSeek Flash vs Pro, or one reminder service deployed three times with different "hours since" thresholds), never a fork.
- Built to run unattended: idempotent re-runs, rate limiting, retry/backoff, graceful degradation, and schema-drift defense.

**→ [Read the full case study](https://wessam-mandour.github.io/)**

---

### 🧰 Toolbox

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-5e44ee?logo=openai&logoColor=white)
![Notion API](https://img.shields.io/badge/Notion_API-000000?logo=notion&logoColor=white)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?logo=twilio&logoColor=white)
![Postmark](https://img.shields.io/badge/Postmark-FFDE57?logoColor=black)
![Slack](https://img.shields.io/badge/Slack-4A154B?logo=slack&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?logo=railway&logoColor=white)
![Regex](https://img.shields.io/badge/Regex-deterministic_parsing-5eead4)
![Technical Writing](https://img.shields.io/badge/Technical_Writing-0d1117)

---

<p align="center"><i>Open to AI Automation and Senior Technical Writer roles.</i></p>
