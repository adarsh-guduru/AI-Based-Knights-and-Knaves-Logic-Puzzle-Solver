# Knights and Knaves Logic Puzzle Solver

## Overview
This project implements an AI solution for solving Knights and Knaves logic puzzles using propositional logic. Inspired by Raymond Smullyan's puzzles, the aim is to determine whether each character in a puzzle is a knight (who always tells the truth) or a knave (who always lies).

## Background
In a Knights and Knaves puzzle:
- Each character is either a knight or a knave.
- A knight's statements are always true.
- A knave's statements are always false.

The objective is to deduce the truth status of each character based on their statements.

## Files
- `logic.py`: Contains helper functions for logical operations (AND, OR, NOT) and for evaluating logical propositions.
- `puzzle.py`: Implements the logic using scenarios with predefined knowledge bases (KB) and uses the functions from `logic.py` to determine the status of characters.

## How to Use
1. Open the `puzzle.py` file to explore the predefined scenarios. Each scenario has its own knowledge base.
2. Run the command below in the terminal to execute the puzzle solver:
   ```bash
   python puzzle.py
