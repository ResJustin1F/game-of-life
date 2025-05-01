# Game of Life

This is a Python implementation of **John Conway’s Game of Life**, a cellular automaton devised in 1970. The simulation models how cells evolve on a grid based on a simple set of rules that mimic natural selection and reproduction.

## About the Project

This project was completed as part of a course project to explore algorithmic logic and visual simulations. The goal was to simulate Conway’s Game of Life both in a text-based format and with a graphical user interface using the `graphics.py` library.

## Rules of the Game

1. Any live cell with fewer than two live neighbors dies (underpopulation).
2. Any live cell with two or three live neighbors lives on to the next generation.
3. Any live cell with more than three live neighbors dies (overpopulation).
4. Any dead cell with exactly three live neighbors becomes a live cell (reproduction).

## Technologies Used

- Python 3
- `graphics.py` library by John Zelle
- `random` and `time` modules

## How It Works

- A grid of cells (50x50) is initialized, with each cell randomly set as alive or dead based on a probability threshold.
- The grid evolves for 500 generations.
- The visual output is displayed in a GUI window where live cells appear in purple and dead cells appear in black.

## How to Run

1. Ensure you have Python 3 installed.
2. Download the repository files, including:
   - `game_of_life.py`
   - `graphics.py`
3. Run the program using the command:
   ```bash
   python game_of_life.py
   ```
4. The simulation window will open and begin evolving automatically.

## What I Learned

- How to implement nested loops and list-based grid structures.
- Application of algorithmic thinking through conditional logic.
- Introduction to simple GUI development using object-oriented graphics.

## Author

**Justin Restrepo**  
Student – Computer Programming & Information Systems  
Farmingdale State College  
[GitHub](https://github.com/ResJustin1F) | [LinkedIn](https://linkedin.com/in/justin-restrepo)
