# ♟ VaultChess

P2P chess in your browser. No server. No account. Free forever on GitHub Pages.

## How to Deploy

1. Create a GitHub repo called `vaultchess` (Public)
2. Upload `index.html` and `manifest.json`
3. Settings → Pages → Branch: main → / (root) → Save
4. Your link: `https://YOUR_USERNAME.github.io/vaultchess`

## How to Play

1. **Player 1** opens the link → clicks **Generate Room Code** → shares the 6-letter code
2. **Player 2** opens the same link → pastes the code → clicks **Join Game**
3. Both players are now connected P2P — play chess!

## Features
- Full chess rules (castling, en passant, promotion, check/checkmate/stalemate)
- Works on iPhone, Android, and PC
- Installable as a home screen app
- No server — WebRTC P2P direct connection
- 100% free via GitHub Pages

## Tech
- PeerJS (WebRTC)
- Google STUN + OpenRelay TURN (free, no account needed)
- Single HTML file
