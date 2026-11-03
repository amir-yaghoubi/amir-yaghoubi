# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

GitHub profile repository (`amir-yaghoubi/amir-yaghoubi`). The only content is `README.md`, which GitHub renders on the profile page at https://github.com/amir-yaghoubi. There is no code, build, lint, or test tooling.

## Editing README.md

- Positioning: Senior Backend Engineer (Go / Rust / Node.js) who now works AI-first and ships full-stack (backend, frontend, mobile, DevOps).
- Section order: capsule-render header + typing SVG + contact badges, About me, How I build: AI-first, Highlights (quantified achievements), What I've been building lately, Open source, Tech stack, GitHub stats, footer.
- Sections are separated by `---`.
- "What I've been building lately" lists only personal side projects (no links if private). Company work (`/w/lyvely`) appears only in Highlights, as generic high-level bullets: never the company name, product names or identifying details. The "lately" table lists only Detoman and telesms. "Open source" lists only PUBLIC repos (`gh repo list amir-yaghoubi --json name,visibility`), so no link 404s.
- Visual palette is Tokyo Night (`1a1b27`, `7aa2f7`, `bb9af7`); stats cards come from `github-profile-summary-cards.vercel.app` with `theme=tokyonight` (the public github-readme-stats instance is paused and returns 503). Stack icons come from `skillicons.dev`. Check that new icon IDs render before adding them.
- Achievement numbers (percentages, latencies, counts) are the owner's claims. Do not invent or change them without explicit instruction.
- Preview rendering with GitHub-flavored Markdown (raw HTML such as `<a>`, `<img>`, `</br>` is allowed on profile READMEs).
