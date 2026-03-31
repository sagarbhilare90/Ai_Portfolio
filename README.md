# Sagar Bhilare — Portfolio

> Lead AI Engineer · GenAI Architect · Data Science Team Lead

A personal portfolio website built as a single HTML file — no dependencies, no build step. Deploy anywhere instantly.

**Live Demo:** [yourname.vercel.app](https://yourname.vercel.app)

---

## 🚀 Features

- Responsive dark-themed design with animated UI
- Custom cursor, scroll animations, grid effects
- Sections: Hero, About, Experience, Skills, Projects, Contact
- **AI Chatbot** — powered by Claude (Anthropic) that answers questions about Sagar

---

## ⚡ Deploy to Vercel (3 steps)

1. Fork or clone this repo
2. Go to [vercel.com/new](https://vercel.com/new) → Import this repo → Click **Deploy**
3. Done! Your site is live at `yourproject.vercel.app`

---

## 🤖 Activating the AI Chatbot

The chatbot uses the Anthropic Claude API. To enable it:

1. Get a free API key at [console.anthropic.com](https://console.anthropic.com)
2. Open `index.html` and find this line (~line 530):
   ```js
   const ANTHROPIC_API_KEY = 'YOUR_ANTHROPIC_API_KEY_HERE';
   ```
3. Replace `YOUR_ANTHROPIC_API_KEY_HERE` with your actual key
4. Save and push — the chatbot is live!

> **Security note:** For production, move the API key to a serverless function (e.g., Vercel Edge Function) so it's not exposed in the browser.

---

## 📁 File Structure

```
portfolio/
├── index.html        # Complete portfolio (single file)
├── README.md         # This file
└── vercel.json       # Vercel deployment config
```

---

## 🛠 Customization

All content is in `index.html`. Search for these to update:

| What to change | Search for |
|---|---|
| Your name | `Sagar Bhilare` |
| Email | `sagarbhilare90@gmail.com` |
| Phone | `7208226914` |
| LinkedIn URL | `linkedin.com/in/sagarbhilare` |
| GitHub URL | `github.com/sagarbhilare` |
| Chatbot knowledge | `SYSTEM_PROMPT` variable |
| API Key | `YOUR_ANTHROPIC_API_KEY_HERE` |

---

## 📄 License

MIT — feel free to use and adapt.
