# Huzaifa Umer

Developer in Melbourne. I build AI agent systems that do real work, and the apps around them: TypeScript and React up front, Python and Postgres behind, all self-hosted on my own Docker and Coolify setup.

When something I build could be useful to someone else, I open-source it. Use it, fork it, or open an issue if you spot something.

[huzaifaumer.com](https://huzaifaumer.com) · [LinkedIn](https://www.linkedin.com/in/huzaifaumer) · hello@huzaifaumer.com

---

## What I've been building

### [TruFlint](https://github.com/devhuzi/truflint)
A money app for people who juggle personal money, job income, a side business and savings in one place. Self-hosted, installable web app on Supabase.

The interesting part: an optional bring-your-own-key assistant that can change your ledger, but only by proposing a change you confirm, with every AI write recorded in an audit log. Row-level security on every table, tested with two tenants side by side.

`TypeScript` `Expo / React Native Web` `Supabase` `Postgres + RLS` `Vitest` `Docker`

### [AI Video Production Hub](https://github.com/devhuzi/ai-video-hub)
Paste in a prompt pack or a narration script and get back a finished short-form video. It chains AI image models, video models (Veo 3.1, Grok) and FFmpeg behind a job queue you can pause, resume, cancel or partly re-run.

Image generation falls back SnapGen → Kie.ai → fal.ai, so one provider having a bad day doesn't kill the whole run.

`Python` `FastAPI` `React` `FFmpeg` `Docker`

### [Tools & Subs Manager](https://github.com/devhuzi/subs-manager)
Keeps track of the software and subscriptions you pay for, what renews next and what you could cancel. One codebase, two runtimes: a local-first desktop app for Windows and macOS, and a self-hostable PWA whose renewal reminders arrive even when it's closed.

`TypeScript` `React` `Electron` `Supabase` `Vitest` `Playwright`

---

## Behind the scenes

Some of my tools stay in private repos because they run my own business, but I'm always happy to talk about how they work:

- **Agent Skills Library:** about 49 Claude Code skills that cover an agency's work end to end, from market research, SEO, UX, design and WordPress builds to ads, video, social, proposals, invoicing and reporting. Each one runs standalone, is versioned, and stays in sync across Claude Code, Codex and Gemini.
- **Website pipeline:** intake form → competitor research → UX plan → copy → design → WordPress build and deploy, with a person approving the plan, the design and the final site.
- **Outreach pipeline:** enriches leads, verifies every email address, writes a personal sequence for each one, and holds everything paused until a person approves it.

---

## Tools I reach for

**AI & automation:** Claude Code (skills, sub-agents, MCP), Python, n8n, OpenRouter

**Apps:** TypeScript, React, React Native / Expo, Electron, FastAPI

**Data & infra:** Supabase, PostgreSQL, Docker, nginx, Coolify, GitHub Actions, Linux

---

Before going deep on software I ran an online Quran school for four years and built every system it ran on: the website, CRMs and a custom learning platform. These days I also run One Step Sol, building websites, online stores and ad campaigns for clients.
