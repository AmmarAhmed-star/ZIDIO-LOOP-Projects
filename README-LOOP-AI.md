# LOOP AI 🤖

**Learn AI. Loop. Level Up.**

LOOP AI is an AI Learning Platform built by **Ammar Ahmed** during the Zidio Development Internship.
Master AI prompts, feedback analysis, and real-world AI skills — with XP, levels, progress sync, leaderboard, certificate, and real AI chat.

🔗 **Live Demo:** https://ammarahmed-star.github.io/ZIDIO-LOOP-Projects/
👨‍💻 **Built by:** Ammar Ahmed
📅 **Year:** 2026

---

## ✨ Features

### 🔐 Login & Progress Sync
- **Login with Google** — One-click Google Sign-In with Firebase Authentication
- **Login with Email** — Email + Password Login / Create Account
- **Progress Auto-Save** — Progress saved in Browser (localStorage) + Cloud (Firebase Firestore)
- **Cross-Device Sync** — Login on any device, your XP and lessons stay synced
- **Logout & Reset** — Logout anytime, Reset progress in one click

### 📈 XP, Levels & Streak
- Every Lesson = XP (20 XP to 50 XP)
- Every 100 XP = Level Up
- Feedback = +10 XP
- Ask AI = +5 XP
- Streak Tracker — Daily learning streak
- Progress Bar — Live XP progress

### 📚 Lessons (4 Lessons)
1. What is AI? — 20 XP
2. How to Write Good Prompts? — 30 XP
3. Build a Resume with ChatGPT — 40 XP
4. How to Earn Money with AI? — 50 XP

### 🏆 Leaderboard — Top Learners
- Top 10 learners ranked by XP
- Live rank — See your own rank
- Refresh Leaderboard button
- Real data from Firebase Firestore + Demo learners

### 🎓 Certificate
- Complete 4/4 Lessons to unlock Certificate
- Certificate shows Name, XP, Level, and Date
- Download / Print Certificate button
- Progress bar shows Certificate progress (0/4 to 4/4)

### 🤖 Real AI Chat — Gemini AI
- **Real Gemini AI** — Powered by Google Gemini API (`gemini-2.0-flash` + `gemini-1.5-flash` fallback)
- **API Key Already Added in Code** — No need to enter key, Real AI is ON on page load
- **Free AI Fallback** — If Gemini key fails / suspended, Free AI (Pollinations) auto-answers
- **Smart Offline Answer** — If no internet, Smart Answer still works
- **Save / Clear Key** — Change or clear key anytime from UI
- Ask anything about AI, Prompts, Resume, Feedback, Earning

### 📊 Feedback Intelligence
- Total Feedback Counter (1284+)
- Positive 68% | Avg Rating 4.2 | Top Theme: Delivery
- Search Feedback — Live filter
- Add Feedback — Your feedback is saved, +10 XP on login

---

## 🛠️ Tech Stack

| Tech | Use |
|------|-----|
| HTML | Structure |
| CSS | Professional + Colorful UI |
| JavaScript | All Logic, XP, Leaderboard, AI Chat |
| Firebase Auth | Google + Email Login |
| Firebase Firestore | Cloud Progress + Leaderboard |
| Gemini API | Real AI Chat |
| Pollinations AI | Free AI Fallback |
| GitHub Pages | Live Hosting |

---

## 📁 Project Structure

```
ZIDIO-LOOP-Projects/
├── index.html          # Main App - All Features (Single File)
├── loop-ai.css         # Optional CSS (if separated)
├── README.md           # This File
```

> Note: The live version uses a single `index.html` with CSS inside, so only 1 file upload is needed.

---

## 🚀 How to Run

### Option 1 — Open Directly
1. Download `index.html`
2. Double-click to open in Browser
3. Login with Google / Email and start learning

### Option 2 — VS Code + Git Bash
```bash
git clone https://github.com/AmmarAhmed-star/ZIDIO-LOOP-Projects.git
cd ZIDIO-LOOP-Projects
# Open index.html with Live Server or double-click
```

### Option 3 — GitHub Pages (Live)
Open: https://ammarahmed-star.github.io/ZIDIO-LOOP-Projects/

---

## 🔑 Gemini API Key Setup

The key is already added in the code as `DEFAULT_GEMINI_KEY`.

To change the key:
1. Go to https://aistudio.google.com/app/apikey
2. Create API Key in a **New Project** (new Google account recommended)
3. Copy the key
4. In `index.html`, replace `DEFAULT_GEMINI_KEY` value
5. Or paste the key in the App UI → Save API Key

> ⚠️ **Security:** Restrict your key in Google AI Studio to `ammarahmed-star.github.io/*` so no one else can use it.

### If Key is Suspended
If you see `Consumer ... has been suspended`:
- That Google Project is suspended, not the LOOP AI app
- Click **Clear Old Key** in the app → Free AI will work
- Create a new key from a **new Google account / new project**

---

## 🔥 Firebase Setup

Firebase Project: `project-a6d7a1f8-6afe-45b4-b06`

To make Login work on your own domain:
1. Firebase Console → Authentication → Sign-in method → Enable **Google** + **Email/Password**
2. Firebase Console → Authentication → Settings → Authorized domains → Add `ammarahmed-star.github.io`
3. Firebase Console → Firestore Database → Create Database → Start in **Test Mode**

---

## 📸 Screenshots

| Login | Dashboard | Leaderboard | Certificate | AI Chat |
|-------|-----------|-------------|-------------|---------|
| Google + Email Login | XP, Level, Streak, Lessons | Top Learners by XP | Unlock on 4/4 Lessons | Real Gemini AI |

---

## 🎯 What I Learned

- Firebase Authentication + Firestore Sync
- Gemini API Integration + Fallback Handling
- XP / Gamification Logic
- Leaderboard + Certificate System
- GitHub Pages Deployment
- Handling Real-World Errors (Suspended API Key, Domain Auth, Cache Issues)

---

## 👨‍💻 Author

**Ammar Ahmed**
- GitHub: https://github.com/AmmarAhmed-star
- LinkedIn: https://www.linkedin.com/in/ammar-ahmed-676825422
- Portfolio: https://ammarahmed-star.github.io/Portfolio-/
- Email: ammarahmed4950@gmail.com

---

## 📄 License

This project is open for learning and portfolio use.

Made with ❤️ by **Ammar Ahmed** • LOOP AI • © 2026
