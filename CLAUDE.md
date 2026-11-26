# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

# Demo Project

This project is a sandbox for learning Claude Code. It exists so you have a real folder to test workflows against, not a tutorial-only environment. It currently holds a static landing page (`index.html`) and no other application.

## Workflow Reminders (for Grant)

These are notes for Grant, not instructions for Claude.

1. **Run `/init`** at the start of any new project to keep this file fresh
2. **Watch the status bar** — when context % crosses 60%, run `/clear`
3. **Run `/security-review`** before pushing anything to GitHub
4. **Use `/plugin`** to install skills (start with front-end design)

## Environment

- **`.env.local`** holds local overrides and is gitignored, so it stays out of commits.
- **Linked GitHub repo:** https://github.com/GHQSTRIDER/demo-project
- **Vercel deployment URL:** *(set after first deploy)*

## Project Goals

*(Update this section as you build things)*

## Architecture

*(Claude will fill this in as the project takes shape)*

## Decisions Made

*(Log non-obvious choices here as they happen — e.g., "chose Postgres over SQLite because we expect concurrent writers")*
