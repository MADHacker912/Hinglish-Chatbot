# 🤖 NOVA — Hinglish AI Chatbot

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)

> A conversational AI chatbot that talks in **Hinglish** (Hindi + English) — just like your dost! Powered by Google Gemini API.

---

## ✨ Features

- 💬 **Hinglish Conversations** — Responds like a real desi friend, not a boring bot
- ⚡ **Real-time Streaming Feel** — Typing animation for a natural chat experience
- 🧠 **Context Memory** — Remembers your full conversation history
- 🎨 **Dark Futuristic UI** — Clean purple-glow aesthetic, fully responsive
- 📱 **Mobile Friendly** — Works great on phone too
- 🔥 **Quick Suggestions** — One-tap starter prompts

---


## 🛠️ Setup

### 1. Clone the repo
```bash
git clone https://github.com/madhacker912/hinglish-ai-chatbot.git
cd hinglish-ai-chatbot
```

### 2. Get Gemini API Key
- Go to [Google AI Studio](https://aistudio.google.com/app/apikey)
- Create a free API key

### 3. Add your API Key
Open `index.html` and replace:
```js
const GEMINI_API_KEY = 'YOUR_GEMINI_API_KEY';
```

### 4. Open in browser
```bash
# Just open index.html — no build step needed!
open index.html
```

---

## 📁 Project Structure

```
hinglish-ai-chatbot/
├── index.html      # Main app (HTML + CSS + JS in one file)
└── README.md       # You are here
```

---

## 🧠 How It Works

1. User types a message in Hinglish
2. Message + full chat history sent to Gemini API
3. Custom system prompt tells Gemini to respond like a desi friend
4. Response displayed with smooth animation

---

## 🎨 Tech Stack

| Tech | Purpose |
|------|---------|
| HTML/CSS/JS | Frontend (zero dependencies!) |
| Google Gemini 2.0 Flash | AI brain |
| Google Fonts (Syne + JetBrains Mono) | Typography |

---

## 🔧 Customization

Want to change NOVA's personality? Edit the `systemPrompt` in `index.html`:

```js
const systemPrompt = `You are NOVA, a friendly AI assistant who speaks in Hinglish...`;
```

---

## 📜 License

MIT License — use karo, share karo, enjoy karo! 🚀

---

## 👨‍💻 Author

**Saksham Gupta** — Vibe Coder from Kanpur 🎯

[![GitHub](https://img.shields.io/badge/GitHub-madhacker912-181717?style=flat&logo=github)](https://github.com/madhacker912)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Saksham--Gupta-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/Saksham-Gupta-9125obito)
[![Portfolio](https://img.shields.io/badge/Portfolio-saksham9125.netlify.app-00C7B7?style=flat&logo=netlify)](https://saksham9125.netlify.app)
