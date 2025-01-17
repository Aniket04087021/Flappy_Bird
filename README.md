﻿# Flappy_Bird

# Flappy Bird Game

A clone of the classic Flappy Bird game implemented in Python using Pygame.

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Contributing](#contributing)
- [License](#license)

## Description

This project is a clone of the Flappy Bird game where the player controls a bird, navigating through gaps in pipes without hitting them. The goal is to achieve the highest score by passing as many pipes as possible.

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/flappy-bird-game.git
    cd flappy-bird-game
    ```

2. **Set up a virtual environment (optional but recommended):**
    ```sh
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Run the game:**
    ```sh
    python game.py
    ```

2. **Controls:**
    - Press the spacebar to make the bird jump.
    - Avoid hitting the pipes and the ground.

## Files

- `game.py`: Main game logic including game loop, score handling, and display.
- `bird.py`: Bird class handling bird movement and drawing.
- `pipe.py`: Pipe class handling pipe generation, movement, and collision detection.
- `menu.py`: Menu class for displaying start, game over, and other menus.
- `requirements.txt`: List of dependencies for the project.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-feature-branch`
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

