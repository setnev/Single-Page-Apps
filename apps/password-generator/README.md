# 🔐 Password Generator

> Generate strong, random passwords entirely in your browser. Nothing is ever sent over the network.

## What It Does

A self-contained password generator that uses the browser's cryptographic random
number generator (`crypto.getRandomValues`) for real entropy — not `Math.random`.
It guarantees at least one character from each selected character set, shuffles the
result, and shows a live strength estimate in bits.

## How To Use

1. Open `index.html` in any modern browser.
2. Drag the **Length** slider and toggle the character sets you want.
3. Click **Generate Password** (or change any option to regenerate).
4. Hit **Copy** to put it on your clipboard.

## Notes

- Runs entirely in the browser — no server, no install, no account.
- Passwords are generated with `crypto.getRandomValues` for cryptographic randomness.
- Your passwords never leave your device.
- Everything lives in a single self-contained `index.html`.

## Tags

`security` `generator` `privacy` `offline`
