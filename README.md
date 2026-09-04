# MyCapsul

**A personal life dashboard plugin for Claude Desktop by Anthropic.**

An agent that knows your world — schedule, finances, goals, health, legal matters — and a dashboard that makes it visible. You chat, it learns.

![MyCapsul Dashboard](https://mycapsul.com/og-image.png)

## What It Does

- **Schedule & Calendar** — Circular clock planner, custody-aware scheduling, event countdowns
- **Finances** — Budget tracking, bill reminders, spending categories, survival timeline
- **Goals & Projects** — Sprint-based project management, backlog grooming, yearly goal tracker
- **Health & Wellness** — ADHD management, energy tracking, medical logging
- **Legal** — Document tracking, violation logs, court date prep
- **Kids & Family** — School events, grade tracking, activity management

## How It Works

A plugin for [Claude Desktop](https://claude.ai/download) (Cowork mode). Install it and Claude keeps a dashboard of your life current as you talk.

Your life data stays on your local machine — no cloud, no accounts. (The page loads web fonts from Google/Adobe, and optional live tiles like News, Weather, and Stocks call third-party services with what you configure.)

## Install

1. Download the latest `mycapsul-v*.zip` from [Releases](https://github.com/mcatoms-xyz/mycapsul/releases)
2. Drop the zip in a folder on your computer — don't unzip it
3. Open a Cowork session in Claude Desktop and select that folder
4. Say "Unzip and set up my MyCapsul"
5. Walk through the 5-step wizard that opens in your browser (Chrome or Edge for automatic sync)

## Links

- **Website**: [mycapsul.com](https://mycapsul.com)
- **Releases & Roadmap**: [mycapsul.com/docs/releases.html](https://mycapsul.com/docs/releases.html)
- **User Guide**: [mycapsul.com/docs/user-guide.html](https://mycapsul.com/docs/user-guide.html)
- **FAQ**: [mycapsul.com/docs/faq.html](https://mycapsul.com/docs/faq.html)

## Tech

Single-file HTML dashboard (~6100 lines). All CSS/JS inline. No build tools; external dependencies are web fonts and Chart.js (FinCapsul only). Dual-layer persistence (localStorage + IndexedDB). Canvas-based visualizations. Satellite module architecture for specialized views (FinCapsul, etc.).

## License

Free and open. Pay what you want via [Buy Me a Coffee](https://buymeacoffee.com/mycapsul).

---

Built by [McAtoms](https://mcatoms.com)
