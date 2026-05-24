# 💊 SuppleTrack

> A lightweight, mobile-first supplement tracker that runs entirely in the browser — no backend, no app store needed.

![HTML](https://img.shields.io/badge/HTML-5-orange?style=flat-square)
![CSS](https://img.shields.io/badge/CSS-3-blue?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat-square)
![PWA](https://img.shields.io/badge/PWA-Ready-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

---

## 🌐 Live Demo

**[https://saifdigital.github.io/suppletrack](https://saifdigital.github.io/suppletrack)**

---

## 📱 Install as an App (Android)

1. Open the live link above in **Chrome** on your Android phone
2. Tap the **3-dot menu** (top right)
3. Tap **"Add to Home screen"**
4. Tap **Add**

SuppleTrack will appear on your home screen and work like a native app — no app store required!

---

## ✨ Features

- **Multiple Supplements** — Track as many supplements as you need
- **Serving Counter** — Log how many servings you've taken today
- **Daily Reset** — Taken count resets automatically each day
- **Cycle Countdown** — Set on/off cycles (e.g. 8 weeks on, 2 weeks off)
- **Rest Period Detection** — App automatically detects when you're in a rest phase
- **Refill Alerts** — Get warned when pills are running low
- **History Log** — See a full log of when you took each supplement
- **Browser Notifications** — Enable reminders directly in the browser
- **Offline Ready** — Works without an internet connection (PWA)
- **No Account Needed** — All data stored locally on your device

---

## 🚀 How to Use

### Add a Supplement
1. Tap the **+ Add** button
2. Enter the supplement name, dosage, and serving count
3. Optionally set cycle days, rest days, and a refill alert threshold
4. Tap **Save**

### Mark as Taken
- Tap **💊 Mark Taken** to log today's full serving
- Or use the **+/−** buttons to adjust the count manually

### Refill
- Tap **🔄 Refill** to reset the pill count back to the total

### Cycle Tracking
- Set **Cycle Days** (e.g. 56 for 8 weeks on)
- Set **Rest Days** (e.g. 14 for 2 weeks off)
- The app will automatically show a rest period banner when you're off-cycle

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure |
| CSS3 | Styling & animations |
| Vanilla JavaScript | App logic |
| localStorage | Data persistence |
| Google Fonts (Syne + DM Sans) | Typography |
| GitHub Pages | Hosting |

No frameworks. No dependencies. No build step. Just one `index.html` file.

---

## 📁 Project Structure

```
suppletrack/
├── index.html        # The entire app (HTML + CSS + JS)
└── README.md         # This file
```

---

## 🔧 Run Locally

No setup required. Just open `index.html` in any browser:

```bash
git clone https://github.com/saifdigital/suppletrack.git
cd suppletrack
open index.html
```

---

## 🗺️ Roadmap

- [ ] Push notification scheduling (daily reminders)
- [ ] Weekly streak tracking
- [ ] Data export (CSV / JSON)
- [ ] Dark/light theme toggle
- [ ] Water intake tracker
- [ ] Notes per supplement

---

## 📄 License

MIT License — free to use, modify, and share.

---

Made with ❤️ by [Saifdigital](https://github.com/saifdigital)
