# Money Week

A mobile-friendly game for an English workshop. Groups manage a weekly budget in Colombian pesos (COP) through 7 days of choices and compete in a ranking.

- Single file: `index.html` (no build step). Host it on Netlify, GitHub Pages or any static host and share the URL as a QR code.
- `SITUATIONS` (near the top of the script) sets how many situations each group plays.
- Shared ranking: create a Firebase Realtime Database (test mode) and paste its URL into `DB_URL`. Without it, the ranking only works on each device.
