# CSCI 1913: Algorithms and Program Development - Project 1

## Project Overview

**Project 1: Word Search** introduces the complexities of handling and manipulating 2D data structures through the development of a word search puzzle generator and solver in Python. This project emphasizes understanding data representation and algorithmic problem-solving in a more extensive programming context than typical assignments.

### Objectives

- Implement functions to generate a word search grid with given words.
- Develop functions to solve word search puzzles by locating words within a grid.
- Utilize data structures effectively to manage 2D grids and solve problems involving string manipulation and direction handling.

### Key Components

- **Data Representation**: Decisions on how to represent grids, locations, directions, and solutions within the program.
- **Letter Grids**: Manage grids as a list of lists of strings, with each string representing a single letter.
- **Locations and Directions**: Implement functionality to navigate through grids using specified locations and directions.
- **Word Search Solver**: Create an algorithm to identify the presence and position of words within a grid.
- **Word Search Generator**: Develop an algorithm to randomly place a list of words into a grid, respecting certain constraints to ensure puzzle solvability.

### Core Functions

1. `get_size(grid)`: Returns the dimensions of the grid.
2. `print_word_grid(grid)`: Prints the grid in a user-friendly format.
3. `copy_word_grid(grid)`: Returns a copy of the given grid.
4. `extract(grid, position, direction, max_len)`: Extracts and returns a string from the grid starting from the specified position and following the given direction up to `max_len`.
5. `show_solution(grid, word, solution)`: Shows the grid with the solution word highlighted.
6. `find(grid, word)`: Searches for a word in the grid and returns its position and direction if found.
7. `find_all(grid, words)`: Finds all given words in the grid and returns their positions and directions.
8. `generate(width, height, words)`: Generates a word search grid of specified dimensions containing the given words.

### Usage

The project is implemented in Python and requires basic familiarity with Python programming. To run any part of the project, navigate to the project directory and execute the Python scripts via command line.

```bash
python word_search.py
