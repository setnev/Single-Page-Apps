# 🟩 Word Guess

> A Wordle-style daily word game that runs entirely offline in a single HTML file.

## What It Does

Word Guess is a Wordle-style daily word game. You have six tries to guess a hidden five-letter word. After each guess, every tile is colored to tell you how close you were: green for a correct letter in the correct spot, yellow for a correct letter in the wrong spot, and gray for a letter that is not in the word. A daily mode gives everyone the same word each day (computed from your local date), and a free-play mode picks a fresh random word whenever you want to keep playing.

## How To Use

1. Open `index.html` in any modern browser (double-click it, or open via `file://`).
2. Type a five-letter word using the on-screen keyboard or your physical keyboard, then press Enter.
3. Read the tile colors: green = right letter, right place; yellow = right letter, wrong place; gray = not in the word.
4. Keep guessing — you get six tries to find the word.
5. Switch between **Daily** (one shared word per day) and **Free play** (random words) using the toggle at the top.
6. Tap the 📊 icon to view your stats, or the ? icon for a quick how-to.

## Notes

- Runs entirely in the browser — no server, no install, no account.
- Everything lives in a single self-contained index.html.
- The word list is built in; daily mode is computed from your local date with no network.

## Tags

`game` `word` `puzzle` `daily` `offline`
