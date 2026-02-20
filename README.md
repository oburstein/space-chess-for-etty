# Etty - Space Chess

A web-based chess game with a space theme featuring an animated starfield, glowing pieces, and full chess rule support.

## Features

- Full chess rules: castling, en passant, pawn promotion, check/checkmate/stalemate detection
- Animated starfield background with nebula glow
- White pieces glow icy blue, black pieces glow purple
- Valid move and capture indicators
- Check and last-move highlighting
- Captured pieces display with material score difference
- Move history log
- Undo, new game, and flip board controls
- Responsive layout

## Setup

```bash
npm install
python3 -m http.server 8080
```

Then open http://localhost:8080 in your browser.

## Tech

- [chess.js](https://github.com/jhlywa/chess.js) for game logic
- Vanilla HTML/CSS/JavaScript
- Canvas-based starfield animation
