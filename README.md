
# 🎮 2D Character Shooter Game (PyGame)

This is a small 2D side-scrolling shooter game I made in 7th class while learning PyGame.
It includes a player character who can move left/right, jump, shoot bullets, and fight an enemy goblin.
I built this project mainly to understand animations, movement, collision, sound effects, and basic game mechanics.

## Demo




## Features

- Smooth character animations (walking left/right & jumping)
- Shooting bullets with sound effects
- Enemy (Goblin) that patrols between two points
- Enemy health bar
- Score system
- Hit detection for both player & enemy
- Background music + sound effects
- Custom sprites & frame-based animation
- Basic physics for jumping
- Game window redraw system


## How It Works
- The game has 3 main objects: Player, Enemy, and Projectile (bullets).
- The player can move using arrow keys and shoot with SPACE.
- The goblin moves automatically between two points; when shot, it loses health.
- If the goblin touches the player, the player takes damage and loses score.
- The game plays walking animations by switching between multiple images quickly.
- Bullets are stored in a list and move across the screen until they hit the enemy or go out of bounds.
- A background image and background music play continuously.
## Installation

Install PyGame:

```bash
  pip install pygame
```
Make sure your folder contains:
- A folder named Images
- A folder named Sound
- All .png images and .wav/.mp3 files used by the game
    
## Deployment

Run the python file:

```bash
  python main.py
```
Replace main.py with your file’s actual name.

## Tech Stack

- Python 3
- PyGame
- Sprite-based animation
- Object-oriented programming
- Basic physics (jumping movement)
- Collision detection between sprites
- Sound & music integration


## Lessons Learned

- How to create animated characters using multiple sprite frames
- How to use classes (player, enemy, projectile) to organize a game
- How to detect collisions using hitboxes
- How background images and music work in PyGame
- Handling movement, jumping, and shooting mechanics
- Updating the screen efficiently using a redraw function
- Building a simple game loop structure


## Future Improvements
- Add a start screen or pause menu
- Add multiple enemies or levels
- Add power-ups (extra health, faster bullets, etc.)
- Add a better scoring system
- Improve character design and animations
- Add a game over screen
- Make the game resolution scalable
## Credits
This project was built with help from the YouTube channel CodeWithHarry, and then extended & customized while learning PyGame