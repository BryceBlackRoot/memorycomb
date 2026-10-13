# MemoryComb

**One memory. Every AI. Your whole team.**

MemoryComb is a memory library that lives on your computer. Claude, ChatGPT and your other AIs all read and write the same memory, so you stop re-explaining yourself every time you switch AIs. Every read has a receipt, and an AI Scorecard shows which AI's facts turned out wrong.

**Built to be trusted:** every memory is checked for hidden instructions before any AI reads it, your AIs can fact-check each other (you settle any disagreement), and your memory stays on your computer with encrypted backups to your own iCloud.

This page has the downloads only. MemoryComb is in early testing on **Mac and Windows** (Windows is newer: tell us what breaks).

## Install (pick one)

By installing MemoryComb you agree to the [License](LICENSE.md). Please also read the [Privacy Policy](PRIVACY.md).

### If you use the Claude app (easiest)
1. Download **memorycomb-*.mcpb** from the [latest release](../../releases/latest).
2. Double-click it. Claude opens its install screen; click **Install**.
   Claude shows a red "not verified" warning for every extension that isn't in its directory yet. What MemoryComb touches: only its own memory folder on your computer (`~/.memorycomb`) and an encrypted daily backup in your iCloud Drive.
3. Start a new chat and ask: **"What's in my MemoryComb?"**

### Mac: Terminal (Claude Code, ChatGPT and everything else)
```bash
curl -fsSL https://github.com/BryceBlackRoot/memorycomb/releases/latest/download/install.sh | sh
```

### Windows: PowerShell (early test)
```powershell
irm https://github.com/BryceBlackRoot/memorycomb/releases/latest/download/install.ps1 | iex
```
It installs MemoryComb for your user only (no admin password), starts it at login, and opens the dashboard's **Get started** page.

## After installing
Your dashboard is at **http://127.0.0.1:8765** (it only opens on your own computer). From there:
- **Get started**: tap the AI you're connecting.
- **Import**: bring in what ChatGPT, Claude, Gemini or Grok already know about you.
- **Team**: share one memory with the people you work with (test version: runs while your computer is on).

## Privacy
Your memory never leaves your computer unless you switch on sharing (for ChatGPT or teammates). MemoryComb goes online only to check for a newer version once a day (it asks for the version number, nothing else), to check a paid license key once a week, and for sharing you switch on.

## Free
MemoryComb is free: unlimited memories, every AI, every trust feature. No trial, no countdown, and nothing is ever deleted.

**Cloud** ($12.99/month, or $119/year) adds sharing projects with teammates, always-on links so ChatGPT and your phone work with your computer off, and encrypted cloud backup. During early testing, team sharing is free and runs from your own computer. Early testers keep a founding price of $9.99/month for life.

## Uninstall
```bash
~/.local/bin/memorycomb uninstall
```
On Windows: `memorycomb uninstall` in PowerShell.
This removes the app and its login item but **keeps your memory** in `~/.memorycomb`. In the Claude app, remove the extension under Settings › Extensions.

## Feedback
Found a problem or have an idea? Open an issue on this page.

## Legal
[License](LICENSE.md) · [Privacy Policy](PRIVACY.md) · [Third-party notices](THIRD_PARTY_NOTICES.md)

MemoryComb is early test software provided as is. Memories and AI answers can be wrong: check anything important yourself. Nothing in MemoryComb is professional advice.
