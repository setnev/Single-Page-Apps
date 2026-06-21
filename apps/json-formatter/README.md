# 🔧 JSON Formatter & Validator
> Paste JSON, get it cleanly formatted, validated, and explorable — entirely offline in your browser.

## What It Does
A single-file tool for working with JSON. It pretty-prints (with selectable 2-space, 4-space, or tab indentation), minifies, and validates JSON. Invalid input gets a clear error message with the line, column, and character position plus a snippet of the offending area. Valid input shows a green "Valid JSON" indicator along with live stats (size in bytes, key count, node count, and nesting depth). You can view output as formatted text or as a collapsible tree, and copy the result with one click.

## How To Use
1. Open `index.html` directly in any modern browser (double-click it — no server needed).
2. Paste or type JSON into the input area on the left (or click **Load sample** to try it out).
3. Click **Format** to pretty-print, **Minify** to compact, or **Validate** to just check it. Choose your indent (2 / 4 / tab) before formatting.
4. Read the green/red status indicator; on errors, check the highlighted line, column, and snippet.
5. Toggle between **Text** and **Tree** views, then use **Copy output** to grab the result. **Clear** wipes everything.

## Notes
- Runs entirely in the browser — no server, no install, no account.
- Everything lives in a single self-contained index.html.
- Your last input is remembered locally via `localStorage` (stays on your device), and copy works even on `file://` via a selection-based fallback.

## Tags
`json` `formatter` `validator` `developer` `offline`
