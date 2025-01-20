# Asteroids Game

A classic arcade-style Asteroids game built using Python and Pygame. Navigate your spaceship, shoot asteroids, and survive as long as possible!

## Features

- **Classic Gameplay:** Inspired by the original Asteroids arcade game.
- **Smooth Controls:** Precise spaceship movement and shooting mechanics.

## Screenshots

![Gameplay Screenshot](path/to/screenshot.png)  
*Example of the game in action*

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Alex-GHP/asteroids.git
    cd asteroids
    ```

2. **Install dependencies:**
    Ensure you have Python installed. Install the required packages using pip:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the game:**
    ```bash
    python main.py
    ```

## Controls

- **W-A-S-D:** Move the spaceship.
- **Spacebar:** Shoot lasers.
- **Escape:** Quit the game.

## How to Play

- Dodge incoming asteroids and shoot them to break them into smaller pieces.
- Avoid collisions with asteroids to stay alive.

## Requirements

- Python 3.7+
- Pygame 2.0+

## File Structure

```
asteroids/
├── __pycache__/       # Compiled Python files
├── venv/              # Virtual environment (not included in repo)
├── .gitignore         # Git ignore file
├── asteroid.py        # Asteroid class
├── asteroidfield.py   # Handles asteroid spawning and behavior
├── circleshape.py     # Circle shape utility
├── constants.py       # Game constants and configuration
├── main.py            # Main game loop
├── player.py          # Player spaceship class
├── requirements.txt   # Python dependencies
├── shot.py            # Handles laser shots
└── README.md          # Project documentation
```

## Contributing

Contributions are welcome! If you'd like to add features, fix bugs, or improve performance, feel free to fork the repository and submit a pull request.

1. Fork the repository
2. Create a new branch for your feature/fix
3. Commit your changes
4. Push the branch to your fork
5. Open a pull request

## Acknowledgments

Enjoy the game? Star this repository and share it with your friends! 🚀
