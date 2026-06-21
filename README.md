# ⚡ Serverless Single Page Apps

> A growing collection of serverless single-page apps and tiny utility apps — no backend, no build step, no install required. Just open in a browser and go.

---

## 🧭 What Is This?

This repository is a curated toolkit of lightweight, self-contained web applications. Every app in this collection:

- **Runs entirely in the browser** — no server, no cloud, no account needed
- **Works on any modern device** — desktop, tablet, or phone
- **Requires zero setup** — open the HTML file and it just works
- **Is fully portable** — host on GitHub Pages, Netlify, a USB drive, or nowhere at all

These are tools built to be useful, readable, and easy to remix.

---

## 📁 Repository Structure

```
/
├── apps/
│   ├── app-name/
│   │   ├── index.html       # The app (self-contained)
│   │   └── README.md        # What it does, how to use it
│   └── ...
├── _template/
│   ├── index.html           # Starter template for new apps
│   └── README.md            # App README template
└── README.md                # You are here
```

Each app lives in its own folder and is **completely self-contained** in a single `index.html` file. No dependencies to install, no package.json, no build pipeline.

---

## 🚀 How To Use Any App

**Option 1 — Run Locally**
```
1. Clone or download this repo
2. Open any app/index.html directly in your browser
```

**Option 2 — Run Online**
```
Browse to the GitHub Pages link for this repo and pick an app.
```

**Option 3 — Host It Yourself**
```
Drop any index.html onto Netlify Drop, Vercel, or any static host.
It will be live in under a minute.
```

---

## 📦 Apps In This Collection

| App | Description | Tags |
|-----|-------------|------|
| [Password Generator](apps/password-generator/) | Cryptographically strong, fully offline password generator | `security` `generator` `privacy` `offline` |
| [Screen Time Quest](apps/screen-time-quest/) | Kids earn screen time by completing chores; optional TOTP parent approval | `family` `kids` `chores` `gamification` `offline` |
| [JSON Formatter & Validator](apps/json-formatter/) | Format, minify, validate & explore JSON with a tree view | `json` `formatter` `developer` `offline` |
| [Regex Tester](apps/regex-tester/) | Live regex matching with highlights, capture groups & cheat sheet | `regex` `developer` `offline` |
| [Base64 Encoder / Decoder](apps/base64-encoder-decoder/) | UTF-8-safe & file Base64 with URL-safe option | `base64` `developer` `offline` |
| [Color Picker + Contrast Checker](apps/color-picker-contrast/) | HEX/RGB/HSL picker with WCAG contrast checking | `color` `design` `accessibility` `offline` |
| [UUID / Token Generator](apps/uuid-token-generator/) | Cryptographically secure UUIDs & random tokens in bulk | `uuid` `token` `security` `offline` |
| [Cron Expression Builder](apps/cron-expression-builder/) | Build cron expressions with plain-English & next-run preview | `cron` `scheduler` `developer` `offline` |
| [File Converter](apps/file-converter/) | Client-side image (PNG/JPEG/WEBP) & CSV⇄JSON conversion | `converter` `images` `csv` `privacy` `offline` |
| [Markdown Editor](apps/markdown-editor/) | Live Markdown editor with multi-doc local save & export | `markdown` `editor` `writing` `offline` |
| [Notes](apps/note-taking/) | Private note-taking with search, tags & JSON backup | `notes` `productivity` `privacy` `offline` |
| [Expense & Budget Tracker](apps/expense-tracker/) | Track income/expenses with charts & monthly budgets | `finance` `budget` `privacy` `offline` |
| [Mortgage / Loan Calculator](apps/mortgage-loan-calculator/) | Payments, amortization schedule & extra-payment savings | `calculator` `mortgage` `finance` `offline` |
| [Macro / Calorie Calculator](apps/macro-calorie-calculator/) | BMR/TDEE, calorie targets & macro splits | `calculator` `fitness` `health` `offline` |
| [Tip Splitter](apps/tip-splitter/) | Split the bill & tip across any number of people | `calculator` `tip` `utility` `offline` |
| [Freelance Rate Calculator](apps/freelance-rate-calculator/) | Find the hourly rate to hit your income goals | `calculator` `freelance` `pricing` `offline` |
| [Retirement Savings Estimator](apps/retirement-savings-estimator/) | Project savings growth & sustainable withdrawals | `calculator` `retirement` `investing` `offline` |
| [Word Guess](apps/word-guess/) | A Wordle-style daily word game with stats | `game` `word` `puzzle` `offline` |
| [Memory Match](apps/memory-match/) | Card matching memory game with difficulty levels | `game` `memory` `cards` `offline` |
| [Typing Speed Test](apps/typing-speed-test/) | Measure WPM & accuracy with timed/word-count modes | `game` `typing` `wpm` `offline` |
| [Resume Analyzer](apps/resume-analyzer/) | AI resume feedback (bring-your-own LLM key) | `ai` `resume` `career` `pluggable-llm` |
| [Cover Letter Generator](apps/cover-letter-generator/) | AI-tailored cover letters (bring-your-own LLM key) | `ai` `cover-letter` `writing` `pluggable-llm` |
| [Text Summarizer](apps/text-summarizer/) | AI summaries in multiple formats (bring-your-own LLM key) | `ai` `summarizer` `productivity` `pluggable-llm` |
| [Prompt Builder & Tester](apps/prompt-builder/) | Compose, test & refine LLM prompts (bring-your-own LLM key) | `ai` `prompt-engineering` `pluggable-llm` |

> Apps will be added here as the collection grows. Each entry links directly to the live demo and source.

---

## 🛠️ Contributing / Adding a New App

Want to add an app? Copy the `_template/` folder, rename it, build your thing, and open a pull request. The only rule: **the entire app must live in one `index.html` file** with no external runtime dependencies.

Guidelines:
- Keep it focused — do one thing well
- Comment your code — this repo is meant to be readable and remixable
- Include a short `README.md` in your app folder describing what it does

---

## 🧱 Philosophy

Most tools on the web require an account, a subscription, an install, or a connection to someone else's server. This collection is a deliberate pushback against that.

These apps are:
- **Offline-capable** by design
- **Privacy-respecting** — your data never leaves your device unless you choose
- **Durable** — an HTML file from this repo will still work in 10 years
- **Understandable** — written to be read, not just run

---

## 📄 License

This project is released under a **Personal Use License** — free to view and run locally for personal use, but commercial use, public hosting, and monetization are strictly prohibited. See the [LICENSE](LICENSE) file for full terms.

---

*Built with a browser, a text editor, and stubbornly zero servers.*
