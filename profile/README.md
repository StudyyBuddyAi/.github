<div align="center">

<img src="https://avatars.githubusercontent.com/u/312015829?s=200&v=4" width="110" alt="StudyBuddy AI logo" />

# StudyBuddy AI

### AI-powered medical education for students across MENA

Turn any topic or your own notes into structured study sheets, flashcards and a grounded question bank — with real PubMed citations.

[![Website](https://img.shields.io/badge/Live-studyybuddyai.com-0EA5E9?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.studyybuddyai.com/)
[![Status](https://img.shields.io/badge/Status-Live%20%C2%B7%20v2.0%20rebuild-22C55E?style=for-the-badge)](https://www.studyybuddyai.com/)
[![Platforms](https://img.shields.io/badge/Platforms-Web%20%C2%B7%20Android%20%C2%B7%20iOS-8B5CF6?style=for-the-badge)](#-products)

</div>

---

## 🩺 What we do

Medical students spend hours turning textbooks into notes. **StudyBuddy AI does that work for them** — and keeps every answer tied to trusted sources.

| | Feature | Description |
|---|---|---|
| 📄 | **Study Sheets** | Type a topic or paste notes → get a clean, structured sheet |
| 🃏 | **Flashcards** | Auto-generated cards for fast review |
| ❓ | **QBank** | Exam-style questions grounded in medical guidelines (RAG) |
| 📚 | **Citations** | Answers linked to PubMed and source guidelines |
| 🧠 | **All systems** | Covers every medical system — pharmacy & pharmacology coming next |
| 🩻 | **Imaging** *(in progress)* | In-platform 2D / 3D medical image viewer |

---

## 🧩 Products

| Repository | Platform | Description |
|---|---|---|
| [`StudybuddyAICodeMap`](https://github.com/StudyyBuddyAi/StudybuddyAICodeMap) | 🌐 Web | Main web app (React + TypeScript) |
| `StudybuddyMobile` | 📱 Android / iOS | Flutter mobile client on the same backend |

---

## 🛠️ Tech stack

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain.js-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenRouter-6566F1?style=flat-square&logoColor=white" />
</p>

```text
User query ─▶ Embedding ─▶ pgvector search (Supabase) ─▶ Grounded prompt ─▶ LLM ─▶ Answer + sources
```

---

## 🗺️ Roadmap — v2.0 rebuild

- [x] Live product with real medical students
- [x] RAG pipeline (ingestion + retrieval) on Supabase pgvector
- [ ] **Sprint 1** — Authentication
- [ ] **Sprint 2** — RAG inside the app (LangChain.js)
- [ ] **Sprint 3** — 2D / 3D medical imaging
- [ ] **Sprint 4** — Payments
- [ ] Flutter mobile app release

---

## 👥 Team

| Name | Role |
|---|---|
| Osama Shehadeh | Project Manager |
| Mohammed Al-Kahlout | Frontend Developer |
| Malak Al-Namra | Backend Developer |
| Roshdi Khwaiter | AI Specialist (RAG & Backend) |
| Layal Al-Husseini | QA Engineer |

---

<div align="center">

**Built for medical students, by a team that cares about accurate learning.**

[🌐 Website](https://www.studyybuddyai.com/) · [📦 Repositories](https://github.com/orgs/StudyyBuddyAi/repositories)

<sub>© 2026 StudyBuddy AI. All rights reserved.</sub>

</div>
