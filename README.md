# Maze-Game
This project is a maze game created using Pygame. In this game, the player navigates an avatar through a maze, collecting points by interacting with different objects while avoiding obstacles like walls and monsters. The game provides a fun and interactive way to practice basic Pygame mechanics, including sprite rendering, keyboard input handling, and game loop implementation.

## Table of Contents
1. Game Overview
2. Features
3. Setup and Installation
4. How to Play
5. Code Structure
6. Contributing

## Game Overview
In the Maze Game, the player controls an avatar that navigates through a maze with the goal of collecting points. Points are collected by encountering specific items in the maze, each represented by a different logo. The game ends when the player collects enough points.
### Objective
- Navigate the maze using keyboard inputs.
- Collect points by interacting with various items.
- Avoid obstacles such as walls and monsters to successfully navigate the maze.

## Features
1. Interactive Maze: The maze consists of different types of tiles, including walls, empty spaces, items that give points, and obstacles.

2. Avatar Movement: The player can move the avatar up, down, left, and right using the keyboard.

3. Point Collection: Interact with specific tiles to earn points and receive on-screen messages.

4. Real-time Feedback: Display messages when interacting with items, enhancing gameplay experience.

## Setup and Installation
### Prerequisites
Python 3.x installed on your system.
Pygame library installed. If not installed, use the following command:
```
pip install pygame
```
### Clone the Repository
To get started with the game, clone the repository to your local machine:
```
git clone https://github.com/yourusername/maze-game.git
cd maze-game
```
### Running the Game 
Once you have cloned the repository and installed the required packages, you can run the game using:
```
python maze_game.py
```
Make sure all the image files (```X.png```, ```_.png```, ```M.png```, ```B.png```, ```E.png```, ```L.png```, ```J.png```, ```H.png```) are in the same directory as the script, or adjust the paths in the code as needed.

## How to Play
Use the following keys to move the avatar: 
```W```: Move Up
```A```: Move Left
```S```: Move Down
```D```: Move Right
```Q```: Quit the game

The game board consists of different tiles:
```X```: Walls - Impassable
```_```: Empty space - Passable
```M```: Monster - Avoid it 
```B```, ```E```, ```L```, ```J```: Items that give points when collected

The goal is to navigate through the maze and collect points by interacting with the items while avoiding obstacles.

## Code Structure
The game is structured into several components:

1. Game Initialization: Setting up Pygame, screen dimensions, and loading images.

2. Game Board: The maze is represented as a 2D list where different characters represent different tiles.

3. Avatar Movement: Logic to move the avatar on the board, including collision detection and point collection.

4. Game Loop: The main game loop handles events, rendering the game board, and updating the display.

## Contributing 
If you'd like to contribute to the project, please fork the repository and use a feature branch. Pull requests are welcome.

### Steps to Contribute

1. Fork the repository

2. Create a feature branch (```git checkout -b feature-branch```)

3. Commit your changes (```git commit -am 'Add new feature'```)

4. Push to the branch (```git push origin feature-branch```)

5. Create a new Pull Request
