# ♟️ Chess Tic-Tac-Toe

A unique hybrid game combining the strategic movement of Chess pieces with the winning objective of Tic-Tac-Toe! Play against a challenging AI or online with friends using peer-to-peer multiplayer.

![Game Preview](https://img.shields.io/badge/Game-Online%20Multiplayer-brightgreen)
![AI Mode](https://img.shields.io/badge/AI-Minimax%20Engine-purple)
![Made With](https://img.shields.io/badge/Made%20With-HTML%2FCSS%2FJS-blue)
![PeerJS](https://img.shields.io/badge/P2P-PeerJS-orange)

## 🎮 Play Now

**[Play Chess Tic-Tac-Toe](https://shadowfull12.github.io/Chess-TicTacToe/Chess%20TIC%20TAC%20TOE.html)**

## 🎯 How to Play

### Objective
Get **4 of your pieces in a row** (horizontally, vertically, or diagonally) on the 4x4 board to win!

### Game Rules

1. **Placement Phase**: Each player must place 3 pieces on the board before they can move any pieces
2. **Movement Phase**: After placing 3 pieces, you can choose to either:
   - Place a new piece from your inventory
   - Move an existing piece on the board
3. **Chess Movement**: Each piece type moves like its chess counterpart:
   - ♙ **Pawn**: Moves 1 square forward, captures diagonally
   - ♜ **Rook**: Moves any number of squares horizontally or vertically
   - ♞ **Knight**: Moves in an "L" shape (2+1 squares)
   - ♝ **Bishop**: Moves any number of squares diagonally
4. **Capturing**: Land on an opponent's piece to capture it (returns to their inventory)
5. **Win Condition**: First player to align 3 pieces in a row wins!

## 🌐 Game Modes

### 🤖 Play vs AI
- Challenge a **smart AI opponent** powered by Minimax algorithm with alpha-beta pruning
- AI evaluates board positions, threats, mobility, and potential wins
- You start as White, colors swap on each rematch
- Perfect for practice and single-player fun!

### 👥 Online Multiplayer

#### Creating a Game
1. Click **"Create Room"**
2. Share the **6-character Room Code** with your friend
3. Wait for them to join

#### Joining a Game
1. Enter your friend's **Room Code**
2. Click **"Join Room"**
3. Start playing!

### 🏠 Local Multiplayer
- Play with a friend on the same device
- Take turns on the same screen

### Features
- 🤖 **Smart AI**: Minimax algorithm with alpha-beta pruning for challenging gameplay
- 🎲 **Random Color Assignment**: Colors are randomly assigned at game start
- 🔄 **Color Swap on Rematch**: Colors alternate each rematch
- 📱 **Mobile Friendly**: Fully responsive design works on phones and tablets
- ⚡ **Real-time P2P**: Direct peer-to-peer connection for minimal latency

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Canvas**: HTML5 Canvas for game rendering
- **Networking**: [PeerJS](https://peerjs.com/) for WebRTC P2P connections
- **Responsive**: CSS Media Queries for mobile support

## 📱 Mobile Support

The game is fully playable on mobile devices with:
- Touch controls for piece selection and movement
- Responsive layout that adapts to screen size
- Optimized inventory display for smaller screens

## 🎨 Game Features

| Feature | Description |
|---------|-------------|
| 4x4 Board | Larger than classic Tic-Tac-Toe for strategic depth |
| Chess Pieces | 4 different piece types with unique movements |
| Move Indicators | Visual circles show valid move locations |
| Capture System | Captured pieces return to opponent's inventory |
| Turn Indicator | Clear display of whose turn it is |
| Win Detection | Automatic detection of 3-in-a-row victory |

## 🚀 Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/ShadowFull12/Chess-TicTacToe.git
   ```

2. Open `Chess TIC TAC TOE.html` in your browser

3. For multiplayer, both players need internet access (uses PeerJS cloud servers)

## 📄 License

This project is open source and available for personal use.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for any improvements!

---

**Made with ❤️ for strategy game lovers**
