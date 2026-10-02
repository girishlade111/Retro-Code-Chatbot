# Retro Code Chatbot

A retro-styled, client-side chatbot interface collection — three standalone HTML demos of a terminal/CRT-inspired chat UI built with vanilla HTML, CSS, and JavaScript. No build step, no dependencies, no backend: just open in a browser and chat.

## Demos

| File | Title | Notes |
|------|-------|-------|
| `html-export (15).html` | Girish Lade Chatbot | Warm paper-toned layout with Courier-type typography |
| `html-export (17).html` | Retro Chatbot Interface | Alternative retro styling variant |
| `html-export (18).html` | Retro Code Chatbot | Chat with code-box rendering; message-sending logic calls a chat-completions API (requires your own API key — the committed file ships with a placeholder) |

## Features

- Retro terminal/CRT aesthetic — monospace typography, loading-bar animations
- Client-side only: zero dependencies, works offline (except the optional API-backed demo)
- Code-box message rendering for formatted code output in chat
- Instant typing-style input with loading indicators

## Tech Stack

- HTML5, CSS3 (custom retro styling), vanilla JavaScript
- No frameworks, no build tools, no package manager

## Quick Start

1. Clone the repo:
   ```bash
   git clone https://github.com/girishlade111/Retro-Code-Chatbot.git
   cd Retro-Code-Chatbot
   ```
2. Open `index.html` (or any `html-export (*).html` file) directly in your browser — that's it.

> `html-export (18).html` posts to a chat-completions endpoint. Replace the `API_KEY` placeholder with your own key before using that variant; never commit a real key.

## Project Structure

```
Retro-Code-Chatbot/
├── index.html            # Landing page linking to all demo variants
├── html-export (15).html # Demo variant 1 — warm paper tone
├── html-export (17).html # Demo variant 2 — retro styling variant
├── html-export (18).html # Demo variant 3 — code-box chat + API option
├── LICENSE
└── README.md
```

## Deploy

Static files — deploy anywhere:
- **GitHub Pages**: enabled on this repo's `main` branch (`/` path)
- Or drag the folder into Netlify / Cloudflare Pages / any static host

## License

See [LICENSE](LICENSE).

---

Built by Girish Lade · [ladestack.in](https://ladestack.in)
