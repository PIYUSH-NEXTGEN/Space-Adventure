# 🚀 Space Adventure

A fun and engaging space shooter game built with Python and Pygame. Navigate your spaceship through enemy attacks, destroy incoming enemies, and aim for the highest score!

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Game Controls](#game-controls)
- [Project Structure](#project-structure)
- [License](#license)

## 📖 About

Space Adventure is a classic arcade-style space shooter game developed with the Pygame library. It was created as a learning project to understand game development fundamentals including:
- Sprite rendering and animation
- Collision detection
- Game state management
- Event handling

This is a great project for beginners interested in learning Python game development!

## ✨ Features

- **Interactive Gameplay** - Move your spaceship and shoot enemies in real-time
- **Multiple Enemies** - Face 5 challenging enemies at once
- **Score Tracking** - Keep track of your score as you destroy enemies
- **Collision Detection** - Accurate collision system for bullets and enemies
- **Game Over Detection** - Game ends when an enemy reaches the bottom of the screen
- **Smooth Controls** - Responsive keyboard controls for optimal gameplay

## 📦 Requirements

- Python >= 3.13
- Pygame >= 2.6.1

## 🔧 Installation

### Using `uv` (recommended)

If you have `uv` installed:

```bash
git clone https://github.com/PIYUSH-NEXTGEN/Space-Adventure.git
cd Space-Adventure
uv run code.py
```

### Using `pip`

Alternatively, you can use pip:

```bash
git clone https://github.com/PIYUSH-NEXTGEN/Space-Adventure.git
cd Space-Adventure
pip install pygame>=2.6.1
python code.py
```

## 🎮 How to Play

1. **Start the Game** - Run the game using the installation instructions above
2. **Destroy Enemies** - Your goal is to eliminate all the enemies before they reach the bottom
3. **Increase Your Score** - Each enemy destroyed adds 1 point to your score
4. **Game Over** - If any enemy reaches the bottom of the screen, the game ends
5. **Restart** - Close and reopen the game to play again

## 🎮 Game Controls

| Key | Action |
|-----|--------|
| ⬅️ **LEFT ARROW** | Move spaceship left |
| ➡️ **RIGHT ARROW** | Move spaceship right |
| **SPACEBAR** | Shoot bullets |

## 📁 Project Structure

```
Space-Adventure/
├── code.py              # Main game script
├── README.md            # This file
├── pyproject.toml       # Project configuration
├── uv.lock             # UV lock file
├── icon.png            # Game window icon
├── player.png          # Player spaceship sprite
├── enemy.png           # Enemy sprite
└── bullet.png          # Bullet sprite
```

### File Descriptions

- **code.py** - The main game engine containing all game logic, collision detection, and rendering
- **icon.png** - Window icon displayed in the taskbar and title bar
- **player.png** - Sprite image for the player's spaceship
- **enemy.png** - Sprite image for enemies
- **bullet.png** - Sprite image for bullets fired by the player

## 🎯 Game Mechanics

### Player Movement
- Use left and right arrow keys to move your spaceship across the screen
- The player is confined within screen boundaries (0-736 pixels)

### Shooting
- Press SPACEBAR to fire bullets
- Only one bullet can be fired at a time
- Bullets move upward from the player position

### Enemy Behavior
- 5 enemies spawn at random positions at the top of the screen
- Enemies move horizontally and drop downward gradually
- When an enemy reaches the bottom, the game ends
- Destroyed enemies respawn at random positions at the top

### Collision Detection
- Uses distance-based collision calculation
- Enemies are destroyed when hit by bullets
- Player loses when an enemy reaches Y position 440 or below

## 🚀 Future Enhancements

Some ideas for improving the game:

- [ ] Sound effects and background music
- [ ] Multiple lives/health system
- [ ] Power-ups and special weapons
- [ ] Different difficulty levels
- [ ] High score leaderboard
- [ ] Pause/resume functionality
- [ ] Better graphics and animations
- [ ] Mobile support with touch controls

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests with improvements.

## 📝 License

This project is open source and available under the MIT License. Feel free to use it for learning purposes.

## 🙋 Author

Created by **PIYUSH-NEXTGEN** as a learning project in game development.

---

**Happy Gaming! 🎮** Enjoy destroying enemies and beating your high score!
