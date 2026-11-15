<div align="center">

![Banner](assets/banner.png)

![Weeks](https://img.shields.io/badge/Weeks%20Completed-29-2F7FD6?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-NetSuite%20%2B%20AI-14B8A6?style=for-the-badge)
![SuiteScript](https://img.shields.io/badge/SuiteScript-2.1-8B5CF6?style=for-the-badge)
![Updated](https://img.shields.io/badge/Updated-Nov%202026-F59E0B?style=for-the-badge)
![Built](https://img.shields.io/badge/Built-In%20Public-EF4444?style=for-the-badge)

### NetSuite Architecture & Engineering Journey

**One concept every week. Real code, real diagrams, real project experience.**

[🧭 Start here](#-start-here) &nbsp;•&nbsp; [🤖 AI Series](#-new-netsuite-ai-series) &nbsp;•&nbsp; [🗺️ Roadmap](#%EF%B8%8F-learning-roadmap) &nbsp;•&nbsp; [📂 Structure](#-repository-structure) &nbsp;•&nbsp; [🤝 Connect](#-connect)

</div>

---

## ⚡ In one minute

> [!TIP]
> This repo is my public NetSuite notebook. Every Sunday I document what I built or learned, push it here, and share it on LinkedIn. It started as architecture and engineering notes (SDF, RESTlets, Suitelets, governance, performance) and now also covers **NetSuite AI** and **connecting AI tools such as Claude to NetSuite**.

| 👤 If you are | 🎯 Start with |
|---|---|
| New to SuiteScript | Weekly notes, in order |
| A developer working on integrations | RESTlet and Suitelet patterns, governance and concurrency |
| A consultant or functional lead | AI Series and the tax and finance documents |
| Evaluating AI for NetSuite | AI Series, Document 01 |

---

## 🧭 Start here

| 📌 Track | 📖 What you get | 🔗 Go |
|---|---|---|
| **🏗️ Weekly Architecture Journey** | One architecture or engineering concept per week, with code and diagrams | [Browse weekly folders](./) |
| **🤖 NetSuite AI Series** | How NetSuite AI grew, how outside AI connects, field notes | [Document 01](./) |
| **🧾 Tax and Finance Series** | Tax architecture, GST, HSN and SAC in NetSuite | [Browse](./) |
| **🛠️ Setup Guides** | SDF setup, tooling, common errors | [Browse](./) |

---

## 🆕 New: NetSuite AI Series

A separate track on how AI is changing everyday NetSuite work, written as learning notes plus field notes from real use.

| # | Document | Status |
|---|---|---|
| 01 | From Text Enhance to the Autonomous Suite: how NetSuite AI grew | ✅ Published |
| FN 01 | Field Note: Connecting Claude AI to NetSuite | 🚧 In progress |
| 02 | AI Connector Service (MCP) deep dive | 📝 Planned |
| 03 | SuiteScript Generative AI (N/llm) in practice | 📝 Planned |
| 04 | ODBC and SuiteAnalytics reporting | 📝 Planned |

---

## 🗺️ Learning roadmap

```mermaid
flowchart LR
    A["🧱 ERP and NetSuite<br/>foundations"] --> B["⚙️ SuiteScript 2.1<br/>and records"]
    B --> C["🔌 Integrations<br/>RESTlets and OAuth"]
    C --> D["🚀 SDF and<br/>deployments"]
    D --> E["📈 Performance<br/>and governance"]
    E --> F["🤖 AI and<br/>MCP integration"]
    classDef n fill:#EAF2FC,stroke:#2F7FD6,stroke-width:2px,color:#0F1B2D;
    classDef ai fill:#F3EEFF,stroke:#8B5CF6,stroke-width:2px,color:#0F1B2D;
    class A,B,C,D,E n;
    class F ai;
```

<details>
<summary><b>📅 Weekly index (click to expand)</b></summary>

| Week | Topic | Folder |
|---|---|---|
| 21 | Tax architecture | [open](./) |
| 22 | GST, HSN and SAC | [open](./) |
| 28 | Advanced Saved Search and Performance | [open](./) |

</details>

---

## 🎯 Focus areas

<details>
<summary><b>🏗️ Architecture and engineering</b></summary>

- SDF (SuiteCloud Development Framework)
- RESTlet + Suitelet architecture patterns
- Multi-environment deployment strategies
- Concurrency and governance handling
- Performance optimization techniques

</details>

<details>
<summary><b>🔌 Integrations</b></summary>

- OAuth 2.0 and token-based authentication patterns
- Scheduled and Map/Reduce sync designs
- Third-party system integration patterns (HR, collaboration tools)

</details>

<details>
<summary><b>🤖 AI and automation</b></summary>

- NetSuite AI features and release timeline
- AI Connector Service and MCP
- Using Claude with NetSuite safely (roles, permissions, human review)

</details>

---

## 📂 Repository structure

```text
NetSuite-Learning/
├── assets/                     # banners, timelines, diagrams
├── Week-XX-Topic-Name/         # one folder per weekly topic
│   ├── README.md               # summary, key takeaways, navigation
│   ├── notes/                  # detailed technical notes
│   ├── diagrams/               # architecture diagrams
│   ├── code/                   # SuiteScript 2.1 snippets and examples
│   └── Topic_WeekXX.docx|pdf   # downloadable document
├── AI-Series/
│   ├── Document-01-New-AI-Features/
│   └── Field-Notes/
└── README.md
```

Each topic folder includes:

- 📖 Detailed technical notes
- 🏗️ Architecture diagrams
- 🧩 Code snippets and implementation examples
- 📄 A downloadable PDF and Word version

---

## 🧰 Conventions used in the code

- SuiteScript **2.1**, modular, with clear separation of concerns
- Governance and error handling shown, not skipped
- Sanitized examples only: **no client data, credentials or confidential logic**

> [!WARNING]
> Examples are simplified for learning. Test in a sandbox before using any pattern in production.

---

## ❓ How to use this repo

1. ⭐ **Star or watch** the repo to follow new weekly drops
2. 📖 Open a weekly folder and read its README first
3. 🧪 Copy the code into a sandbox account and experiment
4. 💬 Open an **Issue** with a question, correction or topic request

---

## 🤝 Connect

<div align="center">

**Built in public. Learning every week.** 🚀

[![GitHub](https://img.shields.io/badge/GitHub-NetSuite--Learning-181717?style=for-the-badge&logo=github)](https://github.com/ManojMohite2002/NetSuite-Learning)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manojmohite2002/)

*Feedback, corrections and topic requests are always welcome.*

</div>
