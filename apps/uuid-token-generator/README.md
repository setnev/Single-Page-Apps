# 🔑 UUID / Token Generator

> Generate UUIDs and cryptographically secure random tokens entirely offline in your browser.

## What It Does

A single-file tool for developers that generates RFC-compliant UUIDs (v4 random, v7 time-ordered, and the NIL UUID) plus customizable random tokens. Token character sets include hex, base62, URL-safe, and your own custom alphabet, with adjustable length and bulk generation up to 1000 at once. It shows a live entropy estimate, supports formatting toggles (uppercase, hyphens, quote-wrapping, comma/newline separation), and lets you copy individual values, copy all, or download the results as a `.txt` file. All randomness comes from the Web Crypto CSPRNG.

## How To Use

1. Open `index.html` in any modern browser (double-click works — no server needed).
2. Pick the **UUID** or **Random Token** tab.
3. For UUIDs: choose the version, set how many to generate, and toggle uppercase / hyphens / quote-wrap.
4. For tokens: choose a character set (or custom alphabet), set length and count, and watch the entropy estimate update.
5. Click **Generate**, then use **Copy** per item, **Copy all**, or **Download .txt**.

## Notes
- Runs entirely in the browser — no server, no install, no account.
- Everything lives in a single self-contained index.html.
- Uses crypto.getRandomValues for cryptographically secure randomness.

## Tags
`uuid` `token` `generator` `security` `developer` `offline`
