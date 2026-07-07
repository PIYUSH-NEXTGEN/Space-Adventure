# 🚀 Space Adventure

Space Adventure is a classic arcade-style space shooter game developed with the Pygame library. It was created as a learning project to understand game development fundamentals including:
- Sprite rendering and animation
- Collision detection
- Game state management
- Event handling

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
