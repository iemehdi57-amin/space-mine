
# SPACE MINE - Project Architecture

## Current Version

The current playable prototype is maintained in index.html.

Features:
- Space mining
- Energy system
- Drill upgrades
- Battery upgrades
- Browser local storage

## Planned Project Structure

space-mine/
├── index.html
├── assets/
│   └── images/
├── css/
│   └── style.css
├── js/
│   ├── game.js
│   ├── storage.js
│   └── telegram.js
├── src/
│   └── worker.js
├── docs/
│   └── architecture.md
└── README.md

## File Responsibilities

- index.html: Main game page
- css/style.css: Game design
- js/game.js: Mining and game mechanics
- js/storage.js: Local storage
- js/telegram.js: Telegram integration
- src/worker.js: Server API

## Security

- Validate Telegram users on the server.
- Never trust balances sent by the browser.
- Keep secret keys on the server.
- Store game data in a server database.

## Development Roadmap

1. Complete prototype
2. Organize project files
3. Connect Telegram Mini App
4. Build secure server storage
5. Add missions and leaderboard
6. Test and prepare release

IMPORTANT:
This is the planned structure.
The current game has not yet been split into these files.
