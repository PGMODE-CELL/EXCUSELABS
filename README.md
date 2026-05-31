# 🧠 ExcuseLab — AI-Powered Excuse Generator

> Craft believable, psychologically-tuned excuses for any situation using AI. Built with vanilla HTML/CSS/JS and powered by **Groq AI (Llama 3.3 70B)** — completely free to run.

![ExcuseLab](https://img.shields.io/badge/AI-Groq%20%7C%20Llama%203.3%2070B-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Deploy](https://img.shields.io/badge/deploy-Netlify-00C7B7)
![No Framework](https://img.shields.io/badge/framework-none-lightgrey)

---

## ✨ Features

- 🤖 **AI-generated excuses** via Groq (Llama 3.3 70B) — fast & free
- 🌐 **7 languages** — English, Hindi, Spanish, French, Arabic, Japanese, Portuguese
- 🎯 **4 audience types** — Boss, Family, Friends, Partner
- 📱 **WhatsApp, Email & plain text** versions for every excuse
- 🧠 **Delivery tips + body language advice** per excuse
- ⭐ **Save favourites** and view generation history
- 🔊 **Text-to-speech** playback
- 🔁 **Regenerate** individual excuses
- 💯 **Conviction score** for each excuse
- 📦 **Single HTML file** — zero dependencies, zero build step

---

## 🚀 Quick Start

### Option 1 — Open Locally
Just download `ExcuseLab.html` and open it in your browser. Done.

---

## 🔑 API Setup (Groq — Free)

This project uses **Groq's free API** with **Llama 3.3 70B**. To use your own key:

1. Go to [console.groq.com](https://console.groq.com)
2. Sign up free (no credit card needed)
3. Create an API key
4. Open `ExcuseLab.html` and find this line:

```js
'Authorization': 'Bearer YOUR_GROQ_API_KEY_HERE'
```

5. Replace with your key and save.

> ⚠️ **Note:** The API key is embedded in the frontend HTML. For a public deployment, consider proxying requests through a serverless function (Netlify Functions, Vercel Edge, Cloudflare Workers) to keep your key secret.

---

## 🛠️ Tech Stack

| Layer | Tech |
|---|---|
| Frontend | Vanilla HTML + CSS + JS (no framework) |
| AI | [Groq API](https://groq.com) — Llama 3.3 70B |
| Fonts | Google Fonts (Syne, Space Mono) |
| Hosting | Netlify / GitHub Pages |
| Build | None — single file |

---

## 📁 Project Structure

```
excuselab/
├── ExcuseLab.html    # The entire app — HTML, CSS, and JS in one file
└── README.md         # This file
```

---

## 🌍 Supported Languages

| Language | Code | Direction |
|---|---|---|
| English | `en` | LTR |
| Hindi | `hi` | LTR |
| Spanish | `es` | LTR |
| French | `fr` | LTR |
| Arabic | `ar` | RTL |
| Japanese | `ja` | LTR |
| Portuguese | `pt` | LTR |

---

## 🧩 How It Works

1. **Choose audience** — Boss, Family, Friends, or Partner
2. **Describe situation** — pick a preset or type anything custom
3. **Set urgency** — Low / Medium / High / Emergency
4. **Pick tone** — Sincere, Casual, Dramatic, Funny, or Professional
5. **Set closeness** — New/Formal → Very Close
6. **Generate** — Groq AI crafts 3 unique, psychologically-tuned excuses
7. **Copy** in WhatsApp, Email, or plain text format

---

## 📜 License

MIT — do whatever you want with it.

---

## 🙏 Credits

- AI by [Groq](https://groq.com) + Meta Llama 3.3 70B
- Built with ❤️ and zero npm installs
