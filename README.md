# nextflows — Personal Expense Tracker MCP Showcase

A static, single-page showcase site for the Personal Expense Tracker MCP
project: the team, the test results, a mobile-conversation preview, and a
live example of what each tool returns when it approves or rejects a
request.

This is a **presentation layer only** — it does not call the real MCP
server. The request/response examples shown for each tool are real fixture
data captured during manual testing, hard-coded into the page.

The actual server lives here:
https://github.com/MohammadYousef-001/Personal-Expenses-Tracker

## Run it locally

No build step, no dependencies. Either:

**Option 1 — just open it**
```bash
open index.html
```
(or double-click `index.html` in your file explorer)

**Option 2 — serve it** (avoids some browsers' restrictions on local file access)
```bash
npx serve .
```
Then open the URL it prints (usually `http://localhost:3000`).

## What's on the page

- **Team** — who owns which tool
- **Results** — the manual test ledger (13/13 passing) and the hardening
  fixes that shipped
- **On your phone** — a static mockup of a Claude conversation using the
  tools
- **The tools** — toggle between an approved and a rejected call for each
  of the three P0 tools
- **Run locally** — how to run the actual MCP server (not this page)

## Structure

```text
nextflows-showcase/
├── index.html   # everything — HTML, CSS, and JS in one file
└── README.md
```
