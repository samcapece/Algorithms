# Algorithms and Program Development - Project 2

## Project Overview

**Project 2: GameGrabber** is designed to explore the principles of object-oriented programming, focusing on inheritance, polymorphism, and encapsulation through the development of a game pack in Java. This project consolidates knowledge about object-oriented design by creating multiple interactive games that share common features and structures.

### Objectives

- Develop a cohesive game pack system that utilizes a base `Game` class and several derived classes representing different games.
- Implement polymorphism and inheritance to manage game behaviors effectively.
- Enhance proficiency in Java programming and object-oriented design patterns.
- Apply debugging and testing skills in a complex application.

### Games Included

- **Hangman**: Guess a word letter-by-letter.
- **NumberGuesser**: Deduce a secret number with hints.
- **RockPaperScissors**: Play against the computer in a classic game.
- **WordJumble**: Solve jumbled words.

### Core Components

- **Abstract Game Class**: Serves as a blueprint for game-specific classes, handling common functionalities and providing a framework for game operations.
- **GameGrabber Class**: Manages the game pack, allowing users to select and play any available game.
- **Utility Classes**: Includes classes for managing word lists and other supporting functionalities.

### Functionality

- Each game operates on simple command-line inputs from the user.
- The games are designed to be intuitive, providing immediate feedback and instructions to the user.
- The system maintains high extensibility, allowing for easy addition of new games without modifying the core structure.

## Installation and Usage

To get started with GameGrabber, you need to have Java installed on your system.

### Clone the Repository

```bash
git clone (link to project)
cd gamegrabber

# Compile Java Files:
javac GameGrabber.java

# Run the game pack:
java GameGrabber

