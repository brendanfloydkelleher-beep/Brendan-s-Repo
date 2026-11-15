# Shough Report

A responsive, browser-based Tyler Shough stats tracker and post-game review dashboard.

## Use it

Open `index.html` in a modern browser. Choose **Log a game** after a game is final and enter the box score. The dashboard calculates season totals, completion percentage, NFL passer rating, game-by-game passing/rushing charts, and an automatically generated review. Game data is stored in that browser's local storage; use **Export data** to download a JSON backup.

## Notes

- This is a personal/manual tracker. It does not connect to a live sports data feed and does not automatically know when a game has ended.
- No real-world box scores are preloaded. Only data entered by the user appears.
- Game review copy is generated from entered stats, and its 0–100 performance score is a simple editorial heuristic, not an official grade.
- The site is a single static HTML file and can be hosted on GitHub Pages.
