# BlunderBoards

A chess blunder trainer with Anki-style spaced repetition. BlunderBoards analyzes your games with Stockfish, finds your blunders, and drills you on the best response until you stop making the same mistakes.

## Setup

1. Export your games as PGN from chess.com (or any other source).
2. Copy the PGN files into the `game history/` folder.
3. Open `index.html` in your browser.
4. Click **Analyze Games** to detect blunders from your PGN files.
5. Use **Save to File** after analysis to embed the results so you don't have to re-analyze on next load.

## Features

- Stockfish engine analysis to detect blunders (≥150 centipawn evaluation drop)
- SM-2 spaced repetition: correctly solved blunders appear less often
- Hint system: highlights the piece to move (penalizes the card interval)
- History navigation: step back through previous puzzles to compare positions
- Pre-analysis: save analyzed blunders directly into the HTML file for instant load

## Piece graphics

Chess piece SVGs are in the `pieces-basic-svg/` folder (Wikipedia CC-BY-SA, Uray M. János).
