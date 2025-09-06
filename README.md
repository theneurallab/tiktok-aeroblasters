# AeroBlasters Game

A thrilling space shooter game implementation using Python and Pygame.

## Requirements

- Python 3.6+
- Pygame library

## Steps to Run this Codebase

1. Fork this repository: `https://github.com/theneurallab/tiktok-aeroblasters.git`
2. Clone your forked repository (replace `YOUR_USERNAME` with your actual GitHub username):

```bash
git clone https://github.com/YOUR_USERNAME/tiktok-aeroblasters.git
```

3. Navigate to the project directory:

```bash
cd tiktok-aeroblasters
```

4. Run the game:

```bash
python main.py
```

## Game Controls:

- **Left Arrow / Mouse Left Side**: Move player left
- **Right Arrow / Mouse Right Side**: Move player right
- **Space / Click on Player**: Shoot bullets
- **ESC or Q**: Quit game
- **Mouse Click**: Navigate menus and restart game

## Game Rules:

- Control your fighter plane and destroy enemy aircraft
- Survive waves of enemies with increasing difficulty
- Collect fuel drops to maintain your fuel level
- Collect powerups for enhanced shooting capabilities
- Each enemy destroyed increases your score
- Game over when health reaches zero or fuel runs out
- Progress through 5 difficulty levels with different enemy types

## Project Structure

```
tiktok-aeroblasters/
├── main.py                    # Main game loop and logic
├── objects.py                 # Game object classes (Player, Enemy, Bullet, etc.)
├── assets/                    # Game assets
│   ├── audio/                 # Sound effects and music
│   │   ├── blast.wav          # Enemy destruction sound
│   │   ├── chopper.mp3        # Helicopter engine sound
│   │   ├── click.mp3          # Menu click sound
│   │   ├── Defrini - Spookie.mp3 # Background music
│   │   ├── fuel.wav           # Fuel/powerup collection sound
│   │   ├── gunshot.wav        # Player shooting sound
│   │   ├── mini_exp.mp3       # Small explosion sound
│   │   └── plane.mp3          # Plane engine sound
│   ├── fonts/                 # Custom fonts
│   │   ├── Aladin-Regular.ttf
│   │   ├── BubblegumSans-Regular.ttf
│   │   ├── DalelandsUncialBold-82zA.ttf
│   │   ├── DroneflyRegular-K78LA.ttf
│   │   └── ghostclan.ttf
│   └── images/                # Game graphics
│       ├── bg.png             # Background image
│       ├── clouds.png         # Cloud overlay
│       ├── logo.png           # Game logo
│       ├── fighter.png        # Menu fighter image
│       ├── plane.png          # Menu plane image
│       ├── player1.png        # Player sprite frame 1
│       ├── player2.png        # Player sprite frame 2
│       ├── fuel.png           # Fuel pickup sprite
│       ├── powerup.png        # Powerup pickup sprite
│       ├── game-shoots.png    # Game shooting interface
│       ├── explosion 2.png    # Explosion sprite
│       ├── explosion spread 1.png # Explosion spread sprite
│       ├── bullets/           # Bullet sprites
│       │   ├── 1.png - 4.png
│       │   └── red_fire.png
│       ├── buttons/           # UI button sprites
│       │   ├── homeBtn.png
│       │   ├── replay.png
│       │   ├── soundOffBtn.png
│       │   └── soundOnBtn.png
│       ├── enemies/           # Enemy plane sprites
│       │   ├── enemy1-1.png, enemy1-2.png
│       │   ├── enemy2-1.png, enemy2-2.png
│       │   └── enemy3-1.png, enemy3-2.png
│       ├── choppers/          # Enemy helicopter sprites
│       │   ├── chopper1-1.png, chopper1-2.png
│       │   └── chopper2-1.png, chopper2-2.png
│       ├── explosion1/        # Small explosion frames
│       │   └── 1.png - 3.png
│       └── explosion2/        # Large explosion frames
│           └── 1.png - 8.png
└── README.md                  # Project documentation
```

Made with ❤️ by [Neural Lab](https://theneurallab.com)
