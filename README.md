<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=2800&pause=900&color=0EA5E9&center=true&vCenter=true&width=900&lines=Mohamed+Hamid;Senior+Software+Engineer+%E2%80%94+Full-Stack;Flutter+%C2%B7+Android+%7C+Python+%C2%B7+FastAPI+%C2%B7+PostgreSQL;LLM+systems+in+production" alt="Typing SVG" />

<br/>

<p>
<b>I build the app — and the system behind it.</b><br/>
<em>27+ applications shipped for clients across the Gulf and MENA, and one product of my own that runs today.</em><br/>
<em>I don't hand off at the API boundary.</em>
</p>

<p>
<a href="https://mohamedhamid.dev/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-0EA5E9?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
<a href="https://www.linkedin.com/in/mohamedhamiddev/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="mailto:mohamedhamidofficial4@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

<p>
<img src="https://komarev.com/ghpvc/?username=MohamedHamid4&label=Profile+Views&color=0EA5E9&style=flat-square" />
<img src="https://img.shields.io/github/followers/MohamedHamid4?label=Followers&style=flat-square&color=0EA5E9" />
<img src="https://img.shields.io/badge/Open_to-Remote_Work-22c55e?style=flat-square" />
</p>

</div>

---

## About

```yaml
name:        Mohamed Hamid
role:        Senior Software Engineer — Mobile & Backend
experience:  3+ years · 27+ applications shipped · 16 clients
stack:       Flutter · Dart · Python · FastAPI · PostgreSQL · Node.js · Laravel
education:   B.Sc. Mobile Application Design & Programming — UCAS Gaza, 2026
             Diploma, Software & Databases — UCAS Gaza, 2023
languages:   Arabic (native) · English (professional working)
location:    Remote · open to relocation to the Gulf
```

I build mobile applications and the production systems behind them: the Flutter client, the Python/FastAPI service, the PostgreSQL schema under it, and the deployment that keeps it running.

**What I care about**

- Code that scales — clear layer boundaries, testable services, no hidden coupling
- Proving it — automated tests and commit guards, not assurances
- Offline-first — a feature that only works online fails when the user needs it most
- Arabic done properly — full RTL, locale-aware fonts and numerals
- AI as a feature, not a gimmick — debounced calls, fallbacks, caching, graceful failure
- Publishing my work for review, and reporting the results that go against me

---

## Tech

| | |
|---|---|
| **Mobile** | Flutter · Dart · Android (Java, Kotlin) · iOS |
| **Backend** | Python · FastAPI · Node.js · PHP · Laravel · REST APIs · WebSockets |
| **Data** | PostgreSQL · MySQL · SQLite · Hive · Firestore |
| **Architecture** | Clean Architecture · MVVM · Repository pattern · BLoC/Cubit · Riverpod · Provider · GetX |
| **Cloud & Ops** | Docker · Linux · Firebase (Auth, Firestore, Storage, FCM, Crashlytics) · CI/CD · Git |
| **AI** | Gemini · OpenAI · LLM integration inside production apps |
| **Integrations** | Stripe · OneSignal · FFmpeg · AdMob · Google Maps |

---

## Selected work

### Sahm Trader — risk-enforcement layer for automated trading

My own product, built end to end and alone. When several automated strategies share one account, each sizes its orders as if it were alone — the account is what fails, and nothing in the stack is watching the account.

A Python/FastAPI backend on PostgreSQL, Docker, an execution bridge to the MetaTrader 5 terminal, a web dashboard and a Flutter client. The layer sits inside the order path: an order can be refused **before it is sent**, rather than reported after it fails, and every refusal is logged with its reason.

60 enforcement checkpoints · 8,662 automated tests across 435 files · 1,204 guard checks on every commit.

I published the architecture on the MQL5 developer forum and invited working engineers to break it — six did, and the strongest objection changed the design: **https://www.mql5.com/en/forum/518057**

*Source is private.*

### Nawa (نواة) — Arabic notes app with AI inside the note

Built for a Gulf client in 30 days. Block editor (text, images, audio, video, tasks, links), offline-first with a pending-operations queue in Hive, real-time sharing over QR, biometric lock, full AR/EN localisation, PDF export. Summarisation, voice-to-text and OCR all run inside the note rather than in a separate chatbot.

### Hasabhali (حسبهالي) — Arabic invoicing with OCR

Point the camera at a paper invoice and it becomes a structured record you can split. Built for the Egyptian market, in Egyptian dialect. The hard part was accuracy: getting the model to read Arabic invoices reliably.

### Sarfli (صرفلي) — AI currency assistant

160+ currencies, with cached and debounced rate requests so the app stays responsive, and an offline fallback that answers from the last known rates when the network or the AI service is down.

### MOOV Editor — mobile video editor

Multi-track timeline, trimming and merging, text overlays, audio sync, real-time preview, and a real FFmpeg export pipeline — built from scratch in Flutter.

### Native Android — Java & Kotlin

Built natively before and alongside the Flutter work: **Read & Cut** (Kotlin, text analysis with text-to-speech over SQLite), **Residential Buildings Manager** (Java, REST API), **Puzzles City** (Java, Room), **Number Sequence** (Java, SQLite), **Cookly** (Java, Firebase).

Flutter makes the UI quick, but storage, lifecycle, persistence and API integration are the same problems underneath. Learning them natively first is why I can debug a Flutter app when the platform layer is what broke.

---

## Reach me

**Portfolio** · [mohamedhamid.dev](https://mohamedhamid.dev/)
**LinkedIn** · [in/mohamedhamiddev](https://www.linkedin.com/in/mohamedhamiddev/)
**Email** · mohamedhamidofficial4@gmail.com

Open to backend, mobile and full-stack roles — remote now, relocation to the Gulf possible.
