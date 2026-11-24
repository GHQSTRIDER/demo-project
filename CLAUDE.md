# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

# Demo Project

This project is a sandbox for learning Claude Code. It exists so you have a real folder to test workflows against, not a tutorial-only environment. It currently holds a static landing page (`index.html`) and no other application.

## Workflow Reminders (for Grant)

1. **Always start in Plan Mode** for new features (Shift+Tab until "plan mode on" shows at the bottom)
2. **Run `/init`** at the start of any new project to keep this file fresh
3. **Watch the status bar** — when context % crosses 60%, run `/clear`
4. **Run `/security-review`** before pushing anything to GitHub
5. **Use `/plugin`** to install skills (start with front-end design)

## Environment

- **GitHub username:** GHQSTRIDER
- **`VERCEL_TOKEN`** is stored as a Windows User environment variable — not in any repo file. The Vercel CLI picks it up automatically. Verify with `$env:VERCEL_TOKEN` in PowerShell.
- **`.env.local`** is gitignored and used for any local overrides (NEVER commit).
- **Linked GitHub repo:** https://github.com/GHQSTRIDER/demo-project
- **Vercel deployment URL:** *(set after first deploy)*

## Project Goals

*(Update this section as you build things)*

## Architecture

*(Claude will fill this in as the project takes shape)*

## Decisions Made

*(Log non-obvious choices here as they happen — e.g., "chose Postgres over SQLite because we expect concurrent writers")*
