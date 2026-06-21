# ⭐ Screen Time Quest

> Turn chores into earned screen time. Kids complete tasks to bank minutes, then redeem them — all tracked offline on one device.

## What It Does

A family-friendly chore-to-screen-time tracker. Each kid completes tasks to bank
minutes, hits streak milestones for bonus minutes, and redeems banked time in
fixed blocks (with a daily cap and a minimum-balance gate). Parents get a
PIN-locked control panel to adjust balances, apply penalties, edit kids and
tasks, and tune the rules.

Optional **parent verification** uses standard TOTP (the same codes as Google
Authenticator, Authy, Microsoft Authenticator) so a parent must approve each task
completion. Both the TOTP engine and the QR code generator are implemented from
scratch in pure JS, so the authenticator setup works with no internet.

## How To Use

1. Open `index.html` in any modern browser (works great on a phone).
2. **First launch:** a 30-second onboarding sets up your kids and a starter pack
   of ~24 chores (or start from scratch).
3. Kids tap a task tile to complete it and bank the minutes.
4. Tap **Redeem screen time** to spend banked minutes in blocks.
5. Tap **🔒 Parent** (default PIN `0000`) to manage kids, tasks, penalties, and settings.

## Notes

- Runs entirely in the browser — no server, no install, no account.
- All data is stored locally via `localStorage` (with an in-memory fallback for
  private mode / `file://`). Your data never leaves the device.
- TOTP is implemented to the RFC 6238 test vectors; the QR generator is validated
  by decode round-trip — so codes match real authenticator apps.
- Everything lives in a single self-contained `index.html`.
- **Change the default parent PIN (`0000`) under 🔒 Parent → Settings.**

## Tags

`family` `kids` `chores` `gamification` `totp` `offline` `privacy`
