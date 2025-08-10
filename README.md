# 🎮 Kivi Game Setup GUI

A Java Swing-based **setup interface** for the "Kivi Game" — a turn-based game where you can configure up to 4 players (human or AI), select unique colors, and start the game with an intuitive, aesthetic UI.

---

## ✨ Features
- **Player Configuration**
  - Choose between:
    - None
    - Human Player
    - Computer (Hard)
    - Computer (Easy)
  - Assign names (auto-generated for computer players)
- **Unique Color Selection**  
  Prevents duplicate colors between players.
- **Dynamic Icons**
  - Displays different icons for player type.
  - Smooth scaled graphics for a polished look.
- **Gradient & Transparent Panels**
  - Aesthetic pink-to-white gradient background.
  - Transparent components for a modern UI.
- **Action Buttons**
  - **Start Game** → launches the Kivi game board.
  - **Restart Setup** → resets all selections.
  - **Display Settings** → opens an additional settings window.



## 🛠️ Tech Stack
- **Language**: Java
- **GUI Toolkit**: Swing
- **OOP Structure**:
  - `SetUpAGameGUI` → main setup frame
  - `Player`, `Human`, `Computer` → game logic entities
  - `KiviBoard` → game board logic & rendering
