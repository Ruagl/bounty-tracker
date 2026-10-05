# 🎯 Bounty Tracker

A lightweight, privacy-first dashboard for tracking your bug bounty programs. No backend, no account — all data stays in your browser's localStorage.

## Features

- 📊 Dashboard with stats: total programs, earned, max potential, by status
- 🔍 Search & filter by status
- 💰 Track rewards (max potential + actually earned)
- 🤖 Automation-allowed flag per program
- 📝 Notes per program (policy notes, findings, etc.)
- 💾 Export/Import as JSON (backup & sync across devices)

## Usage

Just open `index.html` in your browser. Or host it free on GitHub Pages:

1. Go to repo **Settings → Pages**
2. Source: **Deploy from a branch** → `main` → `/ (root)`
3. Open the published URL — your personal tracker is live!

## Program Statuses

| Status | Meaning |
|--------|---------|
| Watchlist | Interesting, not started |
| Researching | Reading policy, mapping scope |
| Hunting | Actively testing |
| Submitted | Report(s) filed, awaiting triage |
| Paid | Bounty received 💰 |
| Rejected | Closed / out of scope |

## License

MIT
