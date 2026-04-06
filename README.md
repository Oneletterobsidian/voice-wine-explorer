# Voice Wine Explorer 🍷

A voice-enabled web app that lets users ask questions about a wine dataset and receive answers in both text and spoken voice.

**Live Demo:** [voice-wine-explorer.vercel.app](https://voice-wine-explorer.vercel.app)

## Features

- Ask questions by voice or text
- AI-powered answers grounded in a real wine dataset (215 wines)
- Spoken voice responses via Web Speech API
- Natural language queries like "best red wines under $50" or "wines from Burgundy"

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Vercel Serverless Function (Node.js)
- **AI:** Anthropic Claude API
- **Speech:** Web Speech API (voice input + text-to-speech)
- **Deployment:** Vercel

## Architecture

```
Browser → Vercel Serverless Function → Anthropic Claude API
```

The API key is stored securely as an environment variable on the server, never exposed to the client.

## Getting Started

1. Clone the repo
2. Deploy to Vercel
3. Add `ANTHROPIC_API_KEY` as an environment variable in Vercel settings
4. Visit your deployment URL

## Example Questions

- Which are the best-rated wines under $50?
- What do you have from Burgundy?
- What's the most expensive bottle?
- Which bottles would make a good housewarming gift?
