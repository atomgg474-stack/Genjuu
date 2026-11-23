# Genjuu

A cozy spirit-card shop game. Buy packs, rip them, grade and restore your best spirits, and grow $60 into a fortune.

- `game.html` is the game. The Genjuu Mac app downloads this file each time it opens, so updating it here updates everyone's game.
- `index.html` is the same game, so it can also be played in a browser through GitHub Pages.
- When changing the game, raise the `GENJUU_BUILD` number at the top of `game.html` so every app knows it's newer.

Saves are never stored here. Each player's progress stays on their own computer.
