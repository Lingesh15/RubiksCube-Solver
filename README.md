# Rubik's Cube Solver

This project is a Rubik's Cube solver implemented in C++. It utilizes pattern databases to efficiently determine the optimal solution for any given cube state.

## Features

- Efficient solving algorithms based on pattern databases.
- Modular design with separate components for the cube model, pattern databases, and solver logic.

## Repository Structure

- **Model/**: Contains the representation of the Rubik's Cube, including its state and operations.
- **PatternDatabases/**: Houses the pattern databases used to optimize the solving process.
- **Solver/**: Implements the algorithms that compute the solution sequences.
- **CMakeLists.txt**: Build configuration file for CMake.
- **main.cpp**: Entry point of the application, demonstrating the solver's usage.
