# ParlayPilot

Standalone installable web app (PWA) built Nov 8, 2026 for Wayne Herrington.

- `index.html` — the whole app (premium dark deck, flip-through ticket windows, Wayne's real Nov 8, 2026 Sunday book as the demo deck, add-a-ticket saved to the device, $1.99/month pricing section).
- `manifest.json` + `service-worker.js` + `icon.svg` — installable to phone home screen: own icon, full-screen, no browser bars.
- `icon-192.png` / `icon-512.png` — PNG icons generated from `icon.svg` for the manifest (Android install prompts want PNGs).

## Launch step (Wayne's GitHub Pages, same home as Vee Vee)
1. Create repo `wayneherrington/parlaypilot` on GitHub.
2. Upload these files to the repo root.
3. Settings → Pages → deploy from `main` branch, root folder.
4. Live at https://wayneherrington.github.io/parlaypilot — then the phone "Install app / Add to Home screen" flow puts it on the home screen like a store app.

## Later product steps (Wayne's calls, not built yet)
- Google Play: Play Console account ($25 + ID), Android App Bundle wrapper, 12-tester / 14-day closed test for a new personal account, review, then live (~3 weeks from a finished build).
- $1.99/month subscription billing.
- Patent / trademark checks.
- Google Ads launch campaign (budget is Wayne's call).
- Real account connectors: Kalshi / Polymarket via their APIs; DraftKings / Courtside / Underdog / Hard Rock via bet-confirmation email + receipt import (no public user APIs exist for those).

Numbers on the demo deck are honest: payouts are shown only where a payout is on file, and fair cash-out reads "Opens with the games" pre-game instead of inventing a number.
