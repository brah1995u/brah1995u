## Hi, I'm Andrii

I build websites, online ordering systems, automations and casual Android games. I work as **Cortex Studio**, mostly for small businesses in Spain.

> These are only the projects I can share publicly. Most of my work is client projects or internal tools, so that code stays private.

### Live websites

- **[Anticapizza](https://www.anticapizza.es)**: pizzeria in Playa de Gandía. Online ordering with delivery zones, Stripe payments, 5 languages, an admin console and an Android app that prints kitchen tickets on a Sunmi printer. *Next.js, React, TypeScript, Supabase, Tailwind*
- **[Al Madina Kebab & Pizza](https://almadina.com.es)**: kebab and pizza restaurant in Gandía. Online menu and ordering, staff console, opening-hours logic and kitchen ticket printing. *Next.js, React, TypeScript, Supabase, Tailwind*
- **[Cortex Studio](https://cortexstudio.es)**: my studio's website. ES/EN, code-split sections, consent-gated analytics, a WebGL background. *React, TypeScript, Vite, Tailwind* · [source](https://github.com/brah1995u/cortex-studio-website)

The two restaurant sites are client projects, so their source code stays private.

### AI agents

- **[AI Support Agent](https://github.com/brah1995u/ai-support-agent)**: a customer-support agent for a fictional bus and train company. Claude with tools (trips, bookings verified by code + email, help center, tickets, handoff), hybrid RAG over the help center (pgvector + full-text, multilingual), live handoff to a human operator, an operator console with per-turn traces (tool calls, tokens, cost, latency), an MCP server and an eval suite in English, Spanish and Ukrainian. Runs on Claude or a local model. *Next.js, TypeScript, Anthropic SDK, Postgres + pgvector, MCP, Vitest*

### Automation

- **[Local Lead Finder](https://github.com/brah1995u/n8n-local-lead-finder)**: finds local restaurants through Google Maps, checks whether they have their own online ordering, scores them as leads and syncs them to Airtable. It has budget guards, safe retries and encrypted backups. *n8n, Python, FastAPI, PostgreSQL, Apify, Playwright, pytest*
- **[Lead Signal Agent](https://github.com/brah1995u/lead-signal-agent)**: finds public conversations where people look for a product like yours and scores each one against an ideal customer profile (intent, fit 0-100, reasons, a suggested reply). Runs on Claude or a local model through Ollama. My rewrite of an MIT-licensed lead-generation script by Gurpreet Kaur: new sources, LLM qualification, SQLite dedupe, CLI, Streamlit UI, tests and an eval set. *Python, Anthropic SDK, Pydantic, Streamlit, pytest*
- **[Reels Content Pipeline](https://github.com/brah1995u/n8n-reels-content-pipeline)**: Airtable buttons drive one n8n workflow of about 86 nodes. It covers reference research, transcription, an AI script with structured output and HeyGen avatar rendering. The workflow is generated from Python. *n8n, Python, OpenAI, AssemblyAI, Apify, HeyGen MCP, Docker*

### Web app

- **[AI Launch Radar](https://github.com/brah1995u/ai-launch-radar)**: discover and compare AI startups through a public API. Filters, shareable URLs, side-by-side comparison, unit and E2E tests. *Next.js, TypeScript, Vitest, Playwright*

### Android games

All three are written in Kotlin with Jetpack Compose. The game logic is pure Kotlin and covered by unit tests.

- **[Lava Flow](https://github.com/brah1995u/lava-flow-android)**: a pipe-rotation puzzle with 30 levels, BFS pathfinding, boosters and an in-game economy.
- **[Frozen Path](https://github.com/brah1995u/frozen-path-android)**: an arcade routing puzzle with a 30-level campaign, an endless mode and a daily mini-game.
- **[Gummy Puzzle Drop](https://github.com/brah1995u/gummy-puzzle-drop-android)**: a falling-block match-3 game with cascades, combos, a shop and daily goals.

### Tech

**TypeScript** · **React** · **Next.js** · **Node.js** · **Python** · **Supabase** · **Tailwind** · **n8n** · **LLM agents** · **Kotlin** · **Jetpack Compose**

### Contact

- Website: [cortexstudio.es](https://cortexstudio.es)
- GitHub: [@brah1995u](https://github.com/brah1995u)
