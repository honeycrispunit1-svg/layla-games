# TOOLS.md - Local Notes

Skills define _how_ tools work. This file is for _your_ specifics — the stuff that's unique to your setup.

## What Goes Here

Things like:

- Camera names and locations
- SSH hosts and aliases
- Preferred voices for TTS
- Speaker/room names
- Device nicknames
- Anything environment-specific

## My Setup

### GitHub Authentication
**Account:** honeycrispunit1-svg  
**Email:** honeycrisp.unit1@gmail.com  
**Method:** Passwordless via Google OAuth

**How to login:**
1. Open Gmail (honeycrisp.unit1@gmail.com) in browser
2. Find email from GitHub with subject like "[GitHub] ..." or security-related
3. Click any GitHub link in the email (e.g., "View settings", "Security log")
4. GitHub login page will appear
5. Click "Continue with Google"
6. Select "Honey Crisp honeycrisp.unit1@gmail.com" account
7. Automatically logged in via OAuth

**No password exists** - authentication is through Google account only.

**Access Token:** Stored in `~/.openclaw/credentials.json` under `github.token` (for git operations)

### GitHub Repository
- **Repo:** honeycrispunit1-svg/layla-games
- **Pages URL:** https://honeycrispunit1-svg.github.io/layla-games/
- **Git Remote:** git@github.com:honeycrispunit1-svg/layla-games.git (or HTTPS with token)

## Why Separate?

Skills are shared. Your setup is yours. Keeping them apart means you can update skills without losing your notes, and share skills without leaking your infrastructure.

---

Add whatever helps you do your job. This is your cheat sheet.
