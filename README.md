# KCK Lunch Wheel of Destiny 🥗🎡

A ridiculous single-file lunch-picking wheel for the crew. Spin to decide where to eat — the odds are heavily Aqui.

## How to run

Open **`index.html`** in any browser (double-click it). No build step, no server.

> **Keep the `sounds/` folder next to `index.html`.** The spin/cheer/fanfare audio loads from there by relative path. If you move or zip the project, include the `sounds/` folder.

## Features

- **Weighted wheel** — pick each spot's % in the Admin panel; wedge counts are worked out automatically (Aqui defaults to 50%).
- **Aqui gets eaten** — landing on Aqui removes 1–3 wedges and re-sizes the rest; state is saved per-browser until you hit **Reset wheel**.
- **Spin by button or by flick** — grab the wheel and whip it; harder pull = faster spin (with a minimum so you can't aim it).
- **DoorDash** opens a second wheel; **boba** is a rare (<1%) jackpot.
- **Chaos mode** — optional random curveballs each spin (warp speed, reverse, boba storm, earthquake, disco, and more).
- **Fireworks, confetti, and sound** on every landing.

## Admin

Click **⚙️ Admin** to edit restaurants, DoorDash options, and percentages. The passcode is set near the top of the `<script>` in `index.html` (`ADMIN_PASSCODE`). Change it before sharing widely — it's stored in plain text in the file, so it's a soft gate, not real security.

## Notes

- All settings persist in the browser's `localStorage` (per browser, per device).
- It's a dumb lunch wheel. Nothing here is exact, by design.
