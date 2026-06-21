# 🔍 Regex Tester
> Build, test, and debug regular expressions with live match highlighting — fully offline.

## What It Does
Regex Tester lets you write a JavaScript regular expression, toggle its flags, and instantly see every match highlighted inside your test string. It lists each match with its position, the matched text, and any numbered or named capture groups, shows a live match count, and clearly reports invalid patterns instead of crashing. A collapsible cheat sheet covers the common tokens, and your last pattern and test string are remembered between visits.

## How To Use
1. Type your pattern into the `/ … /` box (no slashes needed).
2. Tick the flag checkboxes you want — `g`, `i`, `m`, `s`, `u`, `y`.
3. Paste or type text into the Test String area; matches highlight as you type.
4. Read the Matches panel for indices, matched text, and capture groups.
5. Open the cheat sheet anytime for a quick token reference.

## Notes
- Runs entirely in the browser — no server, no install, no account.
- Everything lives in a single self-contained index.html.
- Uses the native `RegExp` engine and guards against infinite loops on zero-width global matches (with a hard match cap), so a pathological pattern won't hang the page.

## Tags
`regex` `developer` `testing` `offline`
