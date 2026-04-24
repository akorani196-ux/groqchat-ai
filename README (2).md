# ⚡ GroqChat AI — Free & Fast AI Chatbot

![HTML](https://img.shields.io/badge/HTML-Single%20File-orange?style=flat-square&logo=html5)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow?style=flat-square&logo=javascript)
![Groq](https://img.shields.io/badge/Powered%20by-Groq%20AI-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Free](https://img.shields.io/badge/API-100%25%20Free-brightgreen?style=flat-square)

A beautiful, fully-featured AI chatbot — **single HTML file**, no installation, no Python, no server required. Just open in your browser and chat!

> Built with Groq API (100% free, no quota limits) + Llama 3.3 70B model.

---

## 📸 Preview

| Chat Interface | File Viewer | Instructions Panel |
|---|---|---|
| Multi-turn conversation with AI | Click any file to read its content | Custom system instructions |

---

## ✨ Features

- 💬 **Multi-turn Chat** — Full conversation memory, context-aware responses
- 📁 **File Upload & Viewer** — Upload TXT, PDF, CSV, JSON, Python, JS, HTML and more. Click any file to read its content directly in the panel
- 🔍 **Ask About Files** — AI reads your uploaded files and answers questions about them
- ⚙️ **System Instructions** — Set custom AI behavior with presets (Expert, Teacher, Coder, Analyst, Urdu, Concise)
- 📂 **Projects** — Switch between named projects (General Chat, Research, Code Helper, Document Q&A)
- 🔑 **API Key Settings** — Stored locally in browser, never sent anywhere except Groq
- 🤖 **Multiple Models** — Llama 3.3 70B, Llama 3.1 8B, Mixtral 8x7B, Gemma 2 9B
- 🔄 **Retry / Regenerate** — Retry last response with one click
- 📋 **Copy Messages** — Copy any AI response
- 📊 **Live Stats** — Files loaded, messages sent, estimated tokens
- 🗑️ **Clear Chat** — Reset conversation anytime
- 📱 **Collapsible Sidebar & Panel** — Clean UI, responsive layout

---

## 🚀 Quick Start

### Step 1 — Download
```bash
git clone https://github.com/YOUR_USERNAME/groqchat-ai.git
```
Or just download `groq_chatbot.html` directly.

### Step 2 — Get Free API Key
1. Go to **[console.groq.com](https://console.groq.com)**
2. Sign up (free, Google login works)
3. Click **API Keys** → **Create API Key**
4. Copy the key (starts with `gsk_...`)

> ✅ Groq is **completely free** — no credit card, no quota limits!

### Step 3 — Run
1. Double-click `groq_chatbot.html` — opens in Chrome/Edge/Firefox
2. Click **🔑 API Settings** tab (right panel)
3. Paste your `gsk_...` key → click **Save**
4. Start chatting! 🎉

---

## 📂 How to Use File Q&A

1. Click the **📁 Files** tab in the right panel
2. Drag & drop any file OR click to browse
3. Uploaded file appears in the list — **click it to read** its content
4. Type your question in the chat box
5. AI will answer based on your file content!

**Supported file types:** `.txt` `.md` `.csv` `.json` `.js` `.py` `.html` `.css` `.ts` `.xml` `.java` `.cpp` `.jsx` `.vue`

---

## 🤖 Available Models

| Model | Best For | Speed |
|-------|----------|-------|
| `llama-3.3-70b-versatile` | Best quality answers | Fast |
| `llama-3.1-8b-instant` | Quick responses | Very Fast |
| `mixtral-8x7b-32768` | Long documents (32k context) | Fast |
| `gemma2-9b-it` | Google's model | Fast |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 / CSS3 | UI & Styling |
| Vanilla JavaScript | All logic, no frameworks |
| Groq API | AI responses (OpenAI-compatible) |
| FileReader API | Local file reading |
| LocalStorage | API key & instructions persistence |
| Plus Jakarta Sans | Typography |
| Fira Code | Monospace / code font |

---

## 📁 Project Structure

```
groqchat-ai/
│
└── groq_chatbot.html      # Complete app — everything in one file
```

This is intentionally a **single-file app**. No build tools, no npm, no dependencies to install.

---

## ⚙️ Configuration

All settings are inside the **API Settings** tab in the app:

| Setting | Default | Description |
|---|---|---|
| API Key | — | Your Groq API key (`gsk_...`) |
| Model | llama-3.3-70b-versatile | AI model to use |
| Max Tokens | 2048 | Maximum response length |
| Temperature | 0.7 | Creativity (0 = precise, 1 = creative) |

---

## 🔐 Privacy & Security

- ✅ Your API key is stored **only in your browser's localStorage**
- ✅ Files are read **locally** — never uploaded to any server
- ✅ Only your **chat messages + file text** are sent to Groq's API
- ✅ No tracking, no analytics, no backend

---

## 🐛 Troubleshooting

| Error | Fix |
|---|---|
| `Invalid API key` | Make sure key starts with `gsk_` and is correctly pasted |
| `Quota exceeded` | Switch to a different Groq model in Settings |
| `Model not found` | Change model in API Settings tab |
| `Network error` | Check your internet connection |
| File not loading | Only text-based files supported (not binary PDFs) |

---

## 🤝 Contributing

Pull requests welcome! Some ideas:

- [ ] Dark mode toggle
- [ ] Export chat as PDF
- [ ] Voice input support
- [ ] Streaming responses
- [ ] PDF text extraction support
- [ ] Multiple language UI

---

## 📜 License

MIT License — free to use, modify, and distribute.

---

## 🙏 Credits

- [Groq](https://groq.com) — Ultra-fast free AI inference
- [Meta Llama](https://llama.meta.com) — Open source LLM
- [Google Fonts](https://fonts.google.com) — Plus Jakarta Sans & Fira Code

---

<div align="center">
Made with ❤️ — Single HTML file, zero dependencies, 100% free
</div>
