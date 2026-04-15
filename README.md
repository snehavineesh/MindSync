# MindSync
 - AI Powered Student Wellness Platform


# MindSync - AI-Powered Student Wellness Platform

**An intelligent burnout detection & peer support application designed specifically for college students**

![MindSync](https://img.shields.io/badge/Status-Demo%20Ready-success)
![React](https://img.shields.io/badge/React-18-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🌟 What Makes MindSync Different

| Existing Apps | MindSync |
|--------------|----------|
| Headspace, Calm — meditation only | **Detects burnout BEFORE it happens** |
| Therapy apps — expensive, scary | **Peer-to-peer, anonymous, free** |
| Generic for all ages | **Built specifically for students** |
| Reactive (after breakdown) | **Proactive — AI flags early signs** |
| No college integration | **Can tie into college calendar/exams** |

---

## ✨ Features

### 📓 Daily Micro-Journal
- **30-second mood check-in** with 3 simple sliders (mood, energy, stress)
- Optional text entry for deeper reflection
- No pressure, no judgment — just honest tracking

### 🧠 AI Burnout Detection
- **NLP sentiment analysis** on journal entries
- **Trend detection** over time with mood/stress patterns
- **Smart risk flagging** (LOW/MEDIUM/HIGH)
- Early intervention before things get bad

### 👥 Anonymous Peer Support Rooms
- **5 topic-based rooms**: Exam Stress, Family Pressure, Imposter Syndrome, Loneliness, Motivation
- **Completely anonymous** — auto-generated names (e.g., BlueMoon42)
- **Real-time chat** with supportive community
- Safe space for vulnerable conversations

### 🔔 Smart Nudges
- Gentle notifications when burnout risk detected
- Suggests peer rooms, breaks, or self-care activities
- **Non-intrusive** — warm recommendations, not alarms

### 📊 Mood Timeline
- **Visual graph** showing mental health trends
- Track correlation with exam periods
- See progress over weeks/months

### 🛡️ Crisis Safety Net
- **Automatic helpline display** for severe distress
- India-specific mental health resources:
  - **iCall**: 9152987821
  - **Vandrevala Foundation**: 1860 2662 345
  - **AASRA**: 9820466726
- Warm, non-scary presentation
- Clear disclaimer about professional help

---

## 🎨 Design Features

### 🌓 Dark/Light Mode
- **Calming color palette** designed for mental wellness
- Smooth transitions between themes
- Eye-friendly for late-night journaling

### 📱 Responsive Design
- Works perfectly on mobile, tablet, and desktop
- Touch-optimized for phones
- Progressive Web App ready

### 🎭 Thoughtful UX
- **No overwhelming UI** — clean, minimal, focused
- **Smooth animations** — fade-ins, slides
- **Encouraging language** — supportive, never judgmental

---

## 🛠️ Tech Stack

### Frontend (Current Demo)
- **React 18** — Component-based UI
- **Recharts** — Beautiful mood timeline graphs
- **Vanilla CSS** — Custom theme system with CSS variables
- **localStorage** — Client-side data persistence (for demo)

### Backend (To Be Built - Week 2)
- **Python Flask** — Lightweight API server
- **HuggingFace Transformers** — Sentiment analysis
  - Model: `distilbert-base-uncased-finetuned-sst-2`
- **NumPy/Pandas** — Burnout risk calculations

### Database (To Be Built - Week 2)
- **Supabase** — Postgres database with real-time features
- Tables:
  - `users` — Student profiles
  - `journal_entries` — Daily check-ins
  - `peer_rooms` — Chat room metadata
  - `messages` — Anonymous chat messages

### Deployment (Week 3)
- **Frontend**: Vercel (free)
- **Backend**: Render (free tier)
- **Database**: Supabase (free tier)

---

## 🚀 Quick Start (Current Demo)

### Option 1: Open Directly
1. Simply open `mindsync.html` in any modern browser
2. Everything works offline — all libraries loaded from CDN
3. Try the dark mode toggle, add journal entries, explore peer rooms!

### Option 2: Local Server (Recommended)
```bash
# Navigate to the project directory
cd /path/to/mindsync

# Start a simple HTTP server
# Python 3
python -m http.server 8000

# OR Python 2
python -m SimpleHTTPServer 8000

# OR Node.js
npx http-server

# Open http://localhost:8000/mindsync.html
```

---

## 📋 What's Working Now (Demo Features)

✅ **Full Dark/Light Mode** — Toggle between themes  
✅ **Daily Journal Entry** — 3 sliders + text input  
✅ **Sample Data** — Pre-loaded entries to show timeline  
✅ **Mood Timeline Chart** — Interactive graph with Recharts  
✅ **Burnout Risk Calculation** — Algorithm based on 7-day trends  
✅ **Smart Alerts** — Risk-based notifications (LOW/MEDIUM/HIGH)  
✅ **Peer Support Rooms** — 5 topic rooms with descriptions  
✅ **Anonymous Chat Interface** — Real-time messaging UI  
✅ **Crisis Helplines** — India-specific mental health resources  
✅ **Responsive Design** — Works on all devices  
✅ **Smooth Animations** — Polished user experience  

---


## 🤝 Contributing

This is currently a demo/prototype. Once the backend is built and deployed, contributions welcome!

**Areas needing help:**
- UI/UX improvements
- ML model fine-tuning for student language
- Regional language support
- Campus beta testing

---

## 📄 License

MIT License — Free to use, modify, and deploy.

**Important:** If you use this code, please:
1. Keep the crisis helpline numbers
2. Include the disclaimer about professional help
3. Credit the original project (optional but appreciated)

---

## 📞 Contact & Support

**Developer:** Sneha Vineesh  
**Location:** Calicut, Kerala, India  
**College:** 6th Semester CS Student  

**Related Projects:**
- **Rhythmic** — Study music website
- **SnapShelter** — Solar-powered shelter pod

---

## 🙏 Acknowledgments

- **HuggingFace** — For open-source NLP models
- **Supabase** — For amazing real-time database
- **iCall, Vandrevala, AASRA** — For mental health support
- **All beta testers** — For feedback and encouragement

---

## 🌟 Star This Repo!

If you find MindSync helpful, please give it a star ⭐ — it helps others discover the project!

**Built with 💜 by students, for students.**

---

**Last Updated:** April 15, 2026  
**Version:** 1.0.0 (Demo)  
**Status:** Frontend Complete ✅ | Backend In Progress 🔨
