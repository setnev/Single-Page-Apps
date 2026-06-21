# 🔄 File Converter

> Convert images (PNG/JPEG/WEBP) and translate between CSV and JSON — entirely in your browser.

## What It Does

File Converter is a 100% client-side tool. It converts images between PNG, JPEG, and WEBP using the browser's `<canvas>` (with a quality slider for lossy formats and original-vs-converted size comparison), and it translates CSV into JSON and JSON back into CSV with a robust parser that correctly handles quoted fields, embedded commas/newlines, and escaped quotes. Nothing is ever uploaded: every conversion runs locally in your browser, so your files stay completely private on your own device.

## How To Use

1. Open `index.html` in any modern browser (double-click works — no server needed).
2. Pick a tab: **Images** or **CSV ⇄ JSON**.
3. **Images:** drag & drop or click to choose one or more images, select the output format, adjust quality for JPEG/WEBP, then press **Convert** and **Download** each result.
4. **CSV ⇄ JSON:** choose a direction and delimiter, paste or upload your data, press **Convert**, then **Copy** or **Download** the output.
5. Watch for clear inline error messages if the input is malformed.

## Notes
- Runs entirely in the browser — no server, no install, no account.
- Everything lives in a single self-contained index.html.
- Your files never leave your device.

## Tags
`converter` `images` `csv` `json` `privacy` `offline`
