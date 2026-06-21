# 🎨 Color Picker + Contrast Checker
> Pick colors, convert between HEX/RGB/HSL, and check WCAG contrast — all offline in one file.

## What It Does
A small, privacy-first color tool. Use the native picker or type a HEX, RGB, or HSL value and the others update live. Every format (HEX, RGB, RGBA, HSL) has a one-click copy button. The WCAG section computes the contrast ratio between a foreground and background color using the correct sRGB relative-luminance formula and shows pass/fail badges for AA and AAA at both normal and large text sizes, with a live preview. A palette helper generates tints, shades, complementary, and analogous colors from the current color.

## How To Use
1. Open `index.html` in any modern browser (double-click works — no server needed).
2. Pick a color with the native picker, or type a HEX / RGB / HSL value; the others sync automatically.
3. Click any **Copy** button to copy that format to your clipboard.
4. Click any palette swatch to make it the current color.
5. In the WCAG Contrast Checker, set foreground and background colors to see the ratio, AA/AAA badges, and a live text preview.

## Notes
- Runs entirely in the browser — no server, no install, no account.
- Everything lives in a single self-contained index.html.
- Contrast uses the WCAG 2.1 sRGB relative-luminance formula: each channel is linearized, weighted (0.2126 R, 0.7152 G, 0.0722 B), and the ratio is `(L_lighter + 0.05) / (L_darker + 0.05)`. Thresholds: normal text AA 4.5:1 / AAA 7:1, large text AA 3:1 / AAA 4.5:1.

## Tags
`color` `design` `accessibility` `wcag` `developer` `offline`
