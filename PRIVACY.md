# MemoryComb Privacy Policy

Effective October 12, 2026.

**The short version:** your memory stays on your computer. We don't collect it, don't see it, and don't run analytics or tracking. MemoryComb goes online for only the few reasons listed below, and you start most of them yourself.

## What stays on your computer
- Your memories, their history, receipts (which AI read what), your settings, and your team list. They're stored in a folder called `.memorycomb` in your home folder.
- Your backup key. It's kept in your computer's own secure store: the Keychain on a Mac, Credential Manager on Windows.

## Backups
Once a day MemoryComb saves an **encrypted** backup to a folder your own cloud service syncs: iCloud Drive on a Mac, OneDrive on Windows, or your Documents folder if neither exists. The backup is locked with your key before it leaves MemoryComb, so Apple or Microsoft only ever store scrambled data. We never receive your backups.

## When MemoryComb goes online
1. **Update check, once a day.** It asks GitHub (where the downloads live) for the latest version number. The request includes MemoryComb's version number. Like any website, GitHub sees your internet address. Nothing else is sent.
2. **License check, once a week, only on a paid plan.** It sends your license key to the store that sold it (Lemon Squeezy) to confirm it's still valid.
3. **Sharing, only when you switch it on.** To let ChatGPT or teammates reach your MemoryComb, a secure link is opened through Cloudflare. While sharing is on, the projects you chose pass through Cloudflare to whoever holds a link. Switch sharing off and the link stops working.
4. **Downloads.** Installing or updating MemoryComb, and switching on sharing the first time, downloads software from GitHub and from the makers of the tools it uses (Astral's uv, Cloudflare's tunnel).

## AI services you connect
When an AI reads your memory (Claude, ChatGPT or another), the memories it reads are sent to that AI company as part of your conversation, under **that company's** privacy policy and your settings there. MemoryComb gives an AI only the memories it asks for. In Claude Code, it also adds a few memories that match your message automatically. Every read is listed in Receipts, so you can see exactly what was shared.

Teammates you add on the Team tab see only the projects you picked for them, through their own AI services.

## What we receive
Nothing, unless you send it to us yourself. For example, you might paste a **problem report** into a message. The report contains version numbers, the health checks, and recent error lines with personal details removed. It never contains your memories or project names.

## Deleting your data
Uninstalling MemoryComb never deletes your memory, so you can't lose it by accident. To delete everything:
- remove the `.memorycomb` folder from your home folder;
- remove the "MemoryComb Backups" folder from your iCloud Drive, OneDrive or Documents;
- remove the backup key ("MemoryComb backup key") from Keychain Access (Mac) or Credential Manager (Windows).

Copies of memories you've already sent to an AI service, or shared with teammates, are covered by those services and people.

## Children
MemoryComb isn't meant for children under 13, and we don't knowingly collect anything from them. In fact, we don't collect anything from anyone.

## Changes and contact
We may update this policy. The date at the top changes when we do, and the current version is always included with MemoryComb and on its download page. Questions: open an issue at https://github.com/BryceBlackRoot/memorycomb. A support email address will be added.
