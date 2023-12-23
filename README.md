# Sudoku Solver

## Overview

This repository contains a Python implementation of a Sudoku solver using two different approaches: backtracking and constraint satisfaction problem (CSP).

## Features

- Two solving approaches: Backtracking and CSP
- Support for standard 9x9 Sudoku puzzles

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/AmirhosseinHanifehzadeh/SudokoSolver.git
    ```

2. Navigate to the project directory:

    ```bash
    cd sudoku-solver
    ```

3. Install any necessary dependencies:

    ```bash
    pip install numpy
    ```


## Backtracking
Backtracking is a recursive algorithm that attempts to solve a problem by trying out different possibilities and undoing any incorrect choices. In the context of Sudoku solving, the backtracking algorithm systematically explores potential solutions, backtracking when it encounters a dead-end, until a valid solution is found.

## Constraint Satisfaction Problem (CSP)
Constraint Satisfaction Problem (CSP) is an approach to problem-solving where the problem is defined in terms of a set of variables, each with a domain of possible values, and a set of constraints that limit the possible combinations of values. In Sudoku solving, CSP is used to model the puzzle as a set of variables (each cell in the grid) with constraints that enforce the rules of Sudoku.
