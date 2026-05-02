# Demo Project

Sandbox for learning Claude Code workflows. See [CLAUDE.md](./CLAUDE.md) for project state and reminders.

## How to use this folder

1. Open this folder in VS Code (`File → Open Folder`)
2. Open the integrated terminal (`Terminal → New Terminal`)
3. Run `claude` to launch Claude Code in this project
4. Press **Shift+Tab** until you see "plan mode on"
5. Tell Claude what you want to build

## What's already configured

- `.gitignore` — protects secrets, build output, and OS junk
- `.vscode/extensions.json` — recommends the Claude Code extension and a few quality-of-life extras
- Git initialized on `main` branch
- Git user identity set globally to `GHQSTRIDER` / `grantforestcollins03@gmail.com`

## Environment variables

The `VERCEL_TOKEN` is stored as a Windows User environment variable — not in any file in this repo. The Vercel CLI picks it up automatically. To verify:

```bash
echo $VERCEL_TOKEN  # bash
echo $env:VERCEL_TOKEN  # PowerShell
```

If you ever rotate the token (Vercel → Account Settings → Tokens), update it in PowerShell:

```powershell
[Environment]::SetEnvironmentVariable('VERCEL_TOKEN', 'new-token-here', 'User')
```
