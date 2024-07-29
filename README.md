# Simp City Game

Welcome to **Simp City**, a city-building strategy game where your goal is to build the happiest and most prosperous city possible!

## Table of Contents
- [Introduction](#introduction)
- [Game Overview](#game-overview)
- [Gameplay](#gameplay)
  - [Main Menu](#main-menu)
  - [Starting a New Game](#starting-a-new-game)
  - [Building Types and Scoring](#building-types-and-scoring)
  - [Game Features](#game-features)
- [Advanced Features](#advanced-features)
- [Requirements](#requirements)
- [How to Run the Game](#how-to-run-the-game)

## Introduction
**Simp City** is a turn-based strategy game developed using Python. Players take on the role of the mayor, aiming to build a thriving city by strategically placing buildings on a 4x4 grid.

## Game Overview
- The game is played over 16 turns.
- Players choose between two randomly-selected buildings each turn and place one on the grid.
- The objective is to maximize the city's score by the end of the game.

## Gameplay

### Main Menu
When the game starts, the main menu provides the following options:
1. **Start new game**: Begin a fresh game with an empty grid.
2. **Load saved game**: Continue from a previously saved game state.
3. **Exit**: Quit the game.

### Starting a New Game
- Upon selecting "Start new game", players receive an empty 4x4 board.
- Two buildings are drawn randomly from the building pool, and players choose one to place on the grid.
- Buildings can be placed freely in the first turn, but subsequent placements must be adjacent to existing buildings.

### Building Types and Scoring
There are five types of buildings, each scoring differently based on their placement:
- **Beach (BCH)**: Scores 3 points if placed in columns A or D, 1 point otherwise.
- **Factory (FAC)**: Scores 1 point per factory, up to 4 points for the first 4 factories.
- **House (HSE)**: Scores based on adjacent buildings, with special rules for factories and beaches.
- **Shop (SHP)**: Scores 1 point for each different type of adjacent building.
- **Highway (HWY)**: Scores 1 point per connected highway in the same row.

### Game Features
- **Building Placement**: Choose between two buildings each turn and place them on the grid.
- **Score Calculation**: The game calculates the current score based on building placement.
- **Save/Load Game**: Players can save their progress and load it later.
- **High Scores**: The game maintains a list of top scores.

## Advanced Features
- **Program Validation**: Includes error checking for inputs and valid building placements.
- **High Scores**: Lists the top 10 players by score.

## Requirements
- Python 3.x
- The game runs in a command-line interface.

## How to Run the Game
1. Ensure Python 3.x is installed on your machine.
  
2. Clone or download the game files.
  
3. Run the game script using the command:
   ```bash
   python BuildingGame.py
   ```
