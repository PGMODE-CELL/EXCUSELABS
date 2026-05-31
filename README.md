# 🧠 ExcuseLab — AI-Powered Excuse Generator

> Craft believable, psychologically-tuned excuses for any situation using AI. Built with vanilla HTML/CSS/JS and powered by **Groq AI (Llama 3.3 70B)** — completely free to run.

![AI](https://img.shields.io/badge/AI-Groq%20%7C%20Llama%203.3%2070B-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Deploy](https://img.shields.io/badge/deploy-Netlify-00C7B7)
![No Framework](https://img.shields.io/badge/framework-none-lightgrey)

---

## ✨ Features

- 🤖 AI-generated excuses via Groq (Llama 3.3 70B) — fast & free
- 🌐 7 languages — English, Hindi, Spanish, French, Arabic, Japanese, Portuguese
- 🎯 4 audience types — Boss, Family, Friends, Partner
- 📱 WhatsApp, Email & plain text versions for every excuse
- 🧠 Delivery tips + body language advice per excuse
- ⭐ Save favourites and view generation history
- 🔊 Text-to-speech playback
- 🔁 Regenerate individual excuses
- 💯 Conviction score for each excuse
- 🔑 Users enter their own free Groq key — no key hardcoded
- 📦 Single HTML file — zero dependencies, zero build step

---

## 🚀 Quick Start

### Option 1 — Open Locally
Download `ExcuseLab.html` and open it in your browser. Done.

### Option 2 — Deploy to Netlify
1. Fork this repo
2. Go to [netlify.com](https://netlify.com) → New site from Git
3. Select this repo
4. Leave build command blank, publish directory as `/`
5. Deploy — it's live!

### Option 3 — Deploy to GitHub Pages
1. Rename `ExcuseLab.html` to `index.html`
2. Go to repo **Settings → Pages**
3. Set source to `main` branch, root `/`
4. Done!

---

## 🔑 API Key (Users provide their own)

No API key is hardcoded. On first visit, users are prompted to enter their own **free Groq key**:

1. Go to [console.groq.com](https://console.groq.com)
2. Sign up free — no credit card needed
3. Create an API key (starts with `gsk_`)
4. Paste it into the prompt on the site

The key is saved in the user's browser (`localStorage`) and never sent anywhere except directly to Groq's API.

---

## 🛠️ Tech Stack

| Layer | Tech |
|---|---|
| Frontend | Vanilla HTML + CSS + JS |
| AI | [Groq API](https://groq.com) — Llama 3.3 70B |
| Fonts | Google Fonts (Syne, Space Mono) |
| Hosting | Netlify / GitHub Pages |
| Build | None — single file |

---

## 📁 Project Structure

```
excuselab/
├── ExcuseLab.html   # Entire app — HTML, CSS, JS in one file
└── README.md        # This file
```

---

## 🌍 Supported Languages

| Language | Direction |
|---|---|
| English | LTR |
| Hindi | LTR |
| Spanish | LTR |
| French | LTR |
| Arabic | RTL |
| Japanese | LTR |
| Portuguese | LTR |

---

## 🧩 How It Works

1. **Choose audience** — Boss, Family, Friends, or Partner
2. **Describe situation** — pick a preset or type anything custom
3. **Set urgency** — Low / Medium / High / Emergency
4. **Pick tone** — Sincere, Casual, Dramatic, Funny, or Professional
5. **Set closeness** — New/Formal → Very Close
6. **Generate** — Groq AI crafts 3 unique psychologically-tuned excuses
7. **Copy** in WhatsApp, Email, or plain text format

---

## 📜 License

MIT — do whatever you want with it.

---

## 🙏 Credits

- AI by [Groq](https://groq.com) + Meta Llama 3.3 70B
- Built with ❤️ and zero npm installs
