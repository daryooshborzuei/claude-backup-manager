# Claude Backup Manager

A free, single-file, browser-based tool to explore, search, and re-export the data you get from Claude's **Settings → Privacy → Export data** feature — conversations, projects, and memory. Built for people whose Claude account was banned, or who simply exported a backup and want an easy way to browse and manage it.

**Live demo:** https://daryooshborzuei.github.io/claude-backup-manager/
*(replace `YOUR-USERNAME` with your actual GitHub username once you've created your account — see the publishing guide below)*

## Why this exists
If your Claude account is suspended, or you simply want a local copy of your data, Anthropic lets you export a ZIP file — but that ZIP is just raw, hard-to-read JSON. This tool turns that export into a readable, searchable, browsable archive, entirely on your own device.

## Features
- Dashboard with usage statistics and activity charts
- Browse and search full conversation history, including attachments and tool activity
- Browse Projects: instructions, per-project memory, and knowledge documents
- View account-wide and per-project memory separately
- Global full-text search across every conversation, project document, and memory entry
- Export conversations, projects, and memory as Markdown
- A guided "Restore to a new account" workflow

## How to use
1. Open the app — either the live link above or `index.html` locally.
2. Request your data export from Claude: Settings → Privacy → Export data.
3. Drag and drop the downloaded `.zip` (or `.dms`) file onto the page, or select the extracted `.json` files individually.
4. Browse, search, and export as needed.

## Privacy
All parsing and rendering happens locally in your browser — the ZIP file you drop is **never uploaded anywhere**. The page does load two external resources on first load: Google Fonts (typography) and JSZip (from cdnjs, to read the ZIP archive). Neither of these receives your export data. For a fully offline-capable copy, download the page once while online, or vendor the JSZip script and fonts locally.

## Disclaimer
This is an independent, community-made tool and is **not affiliated with, endorsed by, or sponsored by Anthropic**. "Claude" is a product of Anthropic, PBC.

## License
Released under the MIT License — see [LICENSE](LICENSE).

## Author
Daryoosh Borzuei
