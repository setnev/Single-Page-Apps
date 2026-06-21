# ⏰ Cron Expression Builder

> Build, parse, and preview standard 5-field cron expressions entirely offline.

## What It Does

A visual and text-based editor for standard 5-field cron expressions (minute, hour, day-of-month, month, day-of-week). Edit the raw cron string or use per-field controls — the two stay in sync. It explains your expression in plain English, validates malformed input with clear errors, and computes the next 5 run times in your local time using its own schedule matcher.

## How To Use

1. Type a cron string in the Expression box, or pick a Quick preset.
2. Use the Visual builder to set each field (Every / Every N / Range / Specific) — the raw string updates automatically, and editing the raw string updates the builder.
3. Read the plain-English description to confirm the schedule means what you intend.
4. Check the Next 5 run times to preview when it will actually fire.
5. Press Copy to put the expression on your clipboard.

## Notes

- Runs entirely in the browser — no server, no install, no account.
- Everything lives in a single self-contained index.html.
- Uses standard 5-field cron; when both day-of-month and day-of-week are restricted they are OR-combined, and the next-run preview is shown in your local time.

## Tags

`cron` `scheduler` `developer` `offline`
