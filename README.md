# Gauntlet

Mobile buylist for Lucas's Pauper gauntlet (Elves, Tron, Blue Terror, Red Madness).
Eka logs each card he buys: price in rupiah, edition and condition.

Live app: https://lucaskodama.github.io/paupergaultet/

- `index.html` – the app
- `config.js` – Firebase web config (shared data between phones)
- `data.js` – suggested prices (TCGplayer market via Scryfall) and printings per card
- `seed.js` – the starting decklists, loaded once into an empty database
- `firestore.rules` – paste into Firebase → Firestore → Rules
