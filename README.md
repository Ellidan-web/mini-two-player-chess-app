♟️ Chess Application
A complete, feature-rich chess game built with vanilla JavaScript that implements all standard chess rules with a clean, interactive interface.

📁 Project Structure
text
CHESS-APP/
├── assets/
│   ├── images/
│   │   └── pieces/
│   │       ├── white/
│   │       │   ├── bishop.png
│   │       │   ├── king.png
│   │       │   ├── knight.png
│   │       │   ├── pawn.png
│   │       │   ├── queen.png
│   │       │   └── rook.png
│   │       └── black/
│   │           ├── bishop.png
│   │           ├── king.png
│   │           ├── knight.png
│   │           ├── pawn.png
│   │           ├── queen.png
│   │           └── rook.png
│   └── styles.css           # All styling & visual design
├── data/
│   ├── data.js              # Board initialization & square management
│   ├── data.json            # Game configuration data
│   └── pieces.js            # Piece definitions & factory functions
├── events/
│   └── global.js            # Main game logic & event handlers
├── helper/
│   ├── commonHelper.js      # Movement calculation & validation utilities
│   ├── constants.js         # Application constants
│   └── modalCreator.js      # Pawn promotion modal system
├── Others/
│   └── HypotheticalBoard.js # Board simulation for move validation
├── render/
│   └── main.js              # DOM rendering & visual updates
├── index.html               # Main HTML file
├── index.js                 # Application entry point
├── package.json             # Project dependencies
├── package-lock.json        # Dependency lock file
└── README.md                # Project documentation
🎯 Features
Core Gameplay
Complete Chess Rules - All standard moves and captures

All Piece Types - Pawns, Knights, Bishops, Rooks, Queens, Kings

Special Moves:

Castling (kingside & queenside)

Pawn promotion with modal selection

En passant captures

Check/checkmate detection

Turn-based System - Alternating white and black moves

Visual Interface
Clean Chess Board - Traditional alternating square colors

Interactive Highlights:

Yellow highlights for possible moves

Red highlights for capture squares

Self-highlighting for selected pieces

Modal Promotions - Beautiful pawn promotion interface

Blur Effects - Visual focus during modal interactions

Technical Excellence
Modular Architecture - Well-organized, maintainable code

Efficient Rendering - Optimized DOM updates

Comprehensive Validation - Legal move checking

State Management - Robust game state tracking

🚀 Quick Start
Download the project files

Open index.html in your web browser

Start Playing - No installation or build process required!

🎮 How to Play
Basic Controls
Click on any piece to select it

View available moves (yellow highlights) and captures (red highlights)

Click on highlighted squares to move

Select promotion piece from modal when pawn reaches opposite side

Special Moves
Castling: Move king two squares toward rook

Pawn Promotion: Choose queen, rook, bishop, or knight

En Passant: Capture pawn that moved two squares

Check: King is under attack - must move out of check

🔧 Technical Modules
Core Modules
index.js - Application bootstrap and initialization

data.js - Creates 8×8 chess board with algebraic notation

pieces.js - Factory functions for all chess pieces

Game Logic
global.js - Main event handling and game flow

commonHelper.js - Movement algorithms and validation

HypotheticalBoard.js - Simulates moves for check detection

User Interface
main.js - Renders board and manages visual updates

modalCreator.js - Handles pawn promotion interface

styles.css - Complete visual styling and animations

Utilities
constants.js - Centralized application constants

data.json - Configuration and game data

🎨 Styling Features
The styles.css in assets provides:

Chess board with traditional colors (#eeeed2 and #769656)

Piece images with proper sizing and cursor interactions

Highlight effects for moves and captures

Modal styling with hover effects

Blur effects for focused gameplay

Responsive design elements

🛠️ Development Notes
Pure JavaScript - No external dependencies or frameworks

Modular Design - Easy to maintain and extend

Efficient Algorithms - Optimized move calculation

Cross-browser Compatible - Works on modern browsers

🔮 Potential Enhancements
Move history and game replay

AI opponent with difficulty levels

Online multiplayer functionality

Game timer and clock

Move sound effects

Save/Load game functionality

PGN import/export for game notation

Start your chess adventure! ♟️ Simply open index.html and enjoy a complete chess experience with all the standard rules and beautiful visuals.

