# CampusBuddy 🎓
### GEC Ajmer — Official Student Assistant

> **30 Days · 30 SIH Solutions** — Day 07  
> Built by **Harish Kumar** · Alpha Coders · GEC Ajmer

---

## What is CampusBuddy?

CampusBuddy is a multilingual campus helpdesk assistant for students of Government Engineering College, Ajmer. Students can ask questions about fees, exams, scholarships, hostel, attendance and placements — in **Hindi, English, Hadoti or Rajasthani**.

No app download needed. Opens directly in any phone browser.

---

## Features

- **Multilingual Support** — Hindi, English, Hadoti, Rajasthani
- **Voice Input & Output** — Speak your question, hear the answer
- **Official Campus FAQ** — Fees, exam dates, attendance rules, scholarships
- **Smart Answers** — Powered by Gemini 2.5 Flash (optional, add your API key)
- **Knowledge Base** — Syncs with Firebase Firestore for live college notices
- **Chat History** — Save and revisit past conversations
- **Admin Panel** — Publish notices and sync college website content
- **Works Offline** — Falls back to local FAQ cache when no internet
- **Single File** — No build step, no install, no dependencies

---

## Live Demo

🔗 **[campusbuddy.vercel.app](https://campusbuddy.vercel.app)**

---

## Tech Stack

| Layer | Technology |
|---|---|
| UI | HTML5 · Tailwind CSS (CDN) · Vanilla JS |
| Fonts | Lexend · Inter · Noto Sans Devanagari |
| Database | Firebase Firestore (compat SDK) |
| Auth | Firebase Anonymous Auth |
| AI | Google Gemini 2.5 Flash API |
| Voice | Web Speech API |
| Hosting | Vercel |

---

## Getting Started

### Run Locally

Just open the file in any browser — no install needed.

```bash
# Clone the repo
git clone https://github.com/hv88786-debug/campusbuddy.git

# Open in browser
open index.html
```

### Enable Smart Answers (Optional)

1. Get a free API key from [aistudio.google.com](https://aistudio.google.com)
2. Open the app → go to **Settings**
3. Paste your key under **Answer Quality**
4. Toggle **Smart Answers** ON

### Connect Firebase (Optional)

1. Create a project at [firebase.google.com](https://firebase.google.com)
2. Enable **Firestore** and **Anonymous Auth**
3. Open `index.html` → find `FIREBASE_CONFIG` in the JS
4. Replace with your project config

---

## SIH Problem Statement

**Problem:** First-year students at regional engineering colleges often miss critical deadlines (fee submission, exam forms, scholarship applications) because information is scattered across notice boards, WhatsApp groups and the college website — and not available in local languages.

**Solution:** CampusBuddy — a single-link campus assistant that answers student queries in their native language, 24/7, without requiring admin intervention.

---

## Project Structure

```
index.html          ← entire app (HTML + CSS + JS)
README.md           ← this file
```

Everything is bundled in one file. No build tools, no node_modules, no deployment complexity.

---

## Screenshots

> Add screenshots here after deployment.

---

## Connect

| Platform | Link |
|---|---|
| GitHub | [@hv88786-debug](https://github.com/hv88786-debug) |
| LinkedIn | [harish-kumar-107161351](https://linkedin.com/in/harish-kumar-107161351) |
| Instagram | [@hv__harish](https://instagram.com/hv__harish) |

---

## License

MIT License — free to use, modify and share.

---

*Part of the **30 Days · 30 SIH Solutions** challenge by Alpha Coders.*
