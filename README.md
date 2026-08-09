<div align="center">

# Jawwad Ahmed
### Full Stack Software Engineer · Django & React · Disciplined Execution

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jawwad-ahmed-875a28324/)
[![Upwork](https://img.shields.io/badge/Upwork-6FDA44?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~010c5a334e3a27a09f?mp_source=share)
[![Portfolio](https://img.shields.io/badge/Live_Projects-FF4500?style=for-the-badge&logo=firefox&logoColor=white)](#-featured-engineering)

![Profile Views](https://komarev.com/ghpvc/?username=RoadtoFire&color=FF4500&style=flat-square&label=Profile+Views)

</div>

---

## 👨‍💻 About Me

I'm a Full Stack Engineer who came to software through **high-stakes Operations & Management** — where deadlines are hard, systems must not fail, and every decision has real consequences.

That background shapes how I build: I don't just write code, I **architect resilient, decoupled systems** with a focus on commercial viability, strict delivery timelines, and maintainable codebases.

Currently building production SaaS platforms with **Django + React**, with a growing footprint in async architecture (Celery/Redis) and API-first design.

> *"Discipline is the bridge between goals and accomplishment."*

---

## 🚀 Featured Engineering

### 📈 [PSX Buffett — Investment Thesis Tracker](https://github.com/RoadtoFire/Investment-Thesis)
> **Python · Pydantic v2 · SQLite · ChromaDB · Streamlit · Playwright · Claude Sonnet · Gemini 1.5 Pro**

A 25-year institutional memory system for a high-conviction portfolio on the Pakistan Stock Exchange. Built around one question on every quarterly result: *"Is the reason I bought this company still true?"*

This is not a trading tool and does not predict prices. It tracks whether the fundamental business thesis for each holding remains intact — using audited financials, live macro data, and LLM reasoning across a portfolio of 7 companies (Meezan Bank, Sazgar Engineering, Fatima Fertilizer, Systems Limited, Lucky Cement, Mari Energies, Dolmen City REIT).

**Key Engineering Decisions:**
- **Equity Risk Premium framework** — calculates a daily GREEN/YELLOW/RED market signal (`KSE-100 Earnings Yield − KIBOR`) before any stock-level analysis; no verdict is written without macro context
- **Dual-LLM pipeline** — Gemini 1.5 Pro for long-context PDF financial statement extraction; Claude Sonnet for thesis reasoning and red flag detection
- **RAG memory via ChromaDB** — corporate briefings indexed for retrieval across quarters, building 25-year institutional context
- **Append-only verdict log** (`VERDICTS.md`) — every quarterly verdict is committed and never edited; the system's long-term memory
- **Pydantic v2 data validation** — all scraped and extracted data passes through typed schemas before touching the database; no dirty data in the archive
- **Multi-source scraping** — PSX portal (Playwright), KIBOR/PKR/CPI (SBP), PAMA vehicle sales, APCMA cement data, OGRA gas price notifications, Brent crude
- **Manual + auto modes** — zero-API-cost manual workflow (paste into Gemini/Claude) or fully automated API pipeline; controlled by a single env flag
- **Explicit sell triggers** per holding — e.g. MEBL flags if CASA ratio drops below 75% for 4 consecutive quarters; FATIMA flags if OGRA equalises gas pricing; no ambiguity about when a thesis is broken

🔗 [Repo](https://github.com/RoadtoFire/Investment-Thesis) ⭐ 6

---

### 🏥 [FRCOphth Pro — Medical Assessment Platform](https://github.com/RoadtoFire/FRCOphth-Pro)
> **Django · PostgreSQL · Render**

A commercial-grade quiz and assessment platform built for a **paying client** in the medical education space — targeting candidates sitting the Fellowship of the Royal College of Ophthalmologists exam.

**Key Engineering Decisions:**
- Secure user authentication with role-based access control
- Dynamic quiz engine pulling randomised questions from a PostgreSQL database
- User progress tracking — past attempts, scores, and performance history persisted per user
- Fully responsive across desktop and mobile

🔗 [Live App](https://frcophth-pro-eu.onrender.com/) · [Repo](https://github.com/RoadtoFire/FRCOphth-Pro) *(demo: `demo_user` / `demo_1234`)*

---

### 🏦 [Amanat — PSX Shariah Portfolio Tracker (API)](https://github.com/RoadtoFire/psx-api)
> **Django DRF · PostgreSQL · Celery · Redis · Railway**

The backend API powering [Amanat](https://amanat-psx.vercel.app) — a production SaaS platform for tracking Shariah-compliant stock portfolios on the Pakistan Stock Exchange. Serves 285 stocks, ~340,000 daily price records, and ~2,800 dividend events via a fully decoupled REST API.

**Key Engineering Decisions:**
- Async background tasks via **Celery + Redis** for automated daily price and dividend updates — zero manual intervention
- Custom purification parser ingests Al-Meezan's semi-annual PDF recomposition reports to extract Zakat ratios per stock
- JWT authentication across a cross-domain frontend/backend setup
- Celery Beat schedule synced to PSX market hours (Mon–Fri, PKT)

🔗 [Live App](https://amanat-psx.vercel.app) · [API Docs](https://trustworthy-spontaneity-production-61c4.up.railway.app/api/docs/) · [Repo](https://github.com/RoadtoFire/psx-api)

---

### 🏥 [FRCOphth Pro — Medical Assessment Platform](https://github.com/RoadtoFire/FRCOphth-Pro)
> *(See above — active client project, ongoing maintenance and feature development.)*

🔗 [Live App](https://frcophth-pro-eu.onrender.com/) · [Repo](https://github.com/RoadtoFire/FRCOphth-Pro)

---

## 🛠 Technical Stack

| Layer | Technologies |
| :--- | :--- |
| **Backend** | Python, Django, Django REST Framework, Celery, Redis |
| **Frontend** | React.js, Vite, Tailwind CSS, Recharts, JavaScript (ES6+) |
| **Databases** | PostgreSQL, SQLite |
| **DevOps & Infra** | Docker, Git, Vercel, Railway, Render, Linux (Xubuntu) |

---

## 📊 GitHub Stats

<div align="center">

![Jawwad's GitHub Stats](https://github-readme-stats.vercel.app/api?username=RoadtoFire&show_icons=true&theme=dark&hide_border=true&title_color=FF4500&icon_color=FF4500&text_color=ffffff&bg_color=0d1117)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=RoadtoFire&layout=compact&theme=dark&hide_border=true&title_color=FF4500&text_color=ffffff&bg_color=0d1117)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=RoadtoFire&theme=dark&hide_border=true&ring=FF4500&fire=FF4500&currStreakLabel=FF4500&background=0d1117)

</div>

---

## 💼 Open to Opportunities

I'm actively available for:

- **Freelance contracts** — Full stack web apps, API development, custom dashboards, business automation
- **MVP development** — From zero to deployed, fast
- **Full-time roles** — Remote-first, technically demanding environments preferred

📬 **Reach me:** [LinkedIn](https://www.linkedin.com/in/jawwad-ahmed-875a28324/) · [Upwork](https://www.upwork.com/freelancers/~010c5a334e3a27a09f?mp_source=share)

📍 Islamabad, Pakistan · UTC+5

---

<div align="center">
<sub>Built with discipline. Deployed with intent.</sub>
</div>
