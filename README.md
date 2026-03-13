# MyCapsul

**A personal life dashboard plugin for Claude Desktop by Anthropic.**

MyCapsul turns Claude into a personal chief of staff. It pairs an AI agent that actually knows your world — your schedule, finances, goals, health, legal matters — with a visual dashboard that makes it all visible.

You chat, it learns. The more you use it, the less you have to explain.

![MyCapsul Dashboard](https://mycapsul.com/og-image.png)

## What It Does

- **Schedule & Calendar** — Circular clock planner, custody-aware scheduling, event countdowns
- **Finances** — Budget tracking, bill reminders, spending categories, survival timeline
- **Goals & Projects** — Sprint-based project management, backlog grooming, yearly goal tracker
- **Health & Wellness** — ADHD management, energy tracking, medical logging
- **Legal** — Document tracking, violation logs, court date prep
- **Kids & Family** — School events, grade tracking, activity management

## How It Works

MyCapsul is a plugin for [Claude Desktop](https://claude.ai/download) (Cowork mode). Install it and Claude becomes context-aware about your personal life, maintaining a living dashboard that updates as you talk.

All data stays on your local machine. No cloud. No accounts. No tracking.

## Install

1. Download the latest `.plugin` file from [Releases](https://github.com/mcatoms-xyz/mycapsul/releases)
2. Open Claude Desktop
3. Go to Settings → Plugins → Install from file
4. Select the `.plugin` file
5. Say "set up my Capsul" to get started

## Links

- **Website**: [mycapsul.com](https://mycapsul.com)
- **Releases & Roadmap**: [mycapsul.com/docs/releases.html](https://mycapsul.com/docs/releases.html)
- **User Guide**: [mycapsul.com/docs/user-guide.html](https://mycapsul.com/docs/user-guide.html)
- **FAQ**: [mycapsul.com/docs/faq.html](https://mycapsul.com/docs/faq.html)

## Tech

Single-file HTML dashboard (~5500 lines). All CSS/JS inline. No external dependencies except fonts. Dual-layer persistence (localStorage + IndexedDB). Canvas-based visualizations. Satellite module architecture for specialized views (FinCapsul, etc.).

## License

Free and open. Pay what you want via [Buy Me a Coffee](https://buymeacoffee.com/mycapsul).

---

Built by [McAtoms](https://mcatoms.com)
