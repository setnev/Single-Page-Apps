# 🔡 Base64 Encoder / Decoder

> Encode and decode text and files to/from Base64 — UTF-8 safe, URL-safe optional, 100% in your browser.

## What It Does

A privacy-first Base64 tool that converts between plain text and Base64 in both directions, with live conversion as you type. It is UTF-8 safe, so emoji and non-ASCII characters round-trip correctly (unlike raw `btoa`/`atob`). It also supports URL-safe Base64 (`-`/`_` with optional padding stripped), and a full file mode: drag/drop or pick any file to Base64-encode it (with image preview, data URI, and a `.txt` download), or paste Base64 to decode it back into a downloadable file.

## How To Use

1. Open `index.html` in any modern browser (double-click works — no server needed).
2. Pick **Encode** or **Decode**, then type or paste into the input; the result updates instantly.
3. Flip **URL-safe** if you need `-`/`_` instead of `+`/`/` (e.g. for tokens or URLs).
4. Use **Copy output**, **Swap ⇄** (to round-trip the result), or **Clear** as needed.
5. In **File mode**, drop or choose a file to get its Base64, data URI, or a `.txt` download — or paste a Base64 string (or `data:` URI), name the file, and click **Decode & download**.

## Notes

- Runs entirely in the browser — no server, no install, no account.
- Everything lives in a single self-contained index.html.
- Text is converted via `TextEncoder`/`TextDecoder`, so it is genuinely UTF-8 safe (emoji and accented characters work); files are read locally with `FileReader` and never leave your device.

## Tags

`base64` `encoder` `decoder` `developer` `offline`
