# Maze Program

## Team members
- [theseChains](https://github.com/theseChains)
- [arseniisemenow](https://github.com/arseniisemenow)


### Introduction

This Maze program is designed to generate and render perfect mazes. It is implemented in C++17 and follows the Google C++ style guide. The GUI is implemented using the Qt library, providing a user-friendly interface for maze interaction.

## Features

- **Generation of Perfect Mazes**: The program automatically generates perfect mazes according to Eller's algorithm. Perfect mazes are defined as mazes in which it is possible to reach each point from any other point in exactly one way.

- **Rendering**: Mazes are rendered on the screen with a field size of 500x500 pixels. The walls have a thickness of 2 pixels, and the size of maze cells is calculated to occupy the entire allotted field.

- **Loading Mazes**: The program allows users to load mazes from files in a specified format. The maximum size of the maze is 50x50.

- **Solving Mazes**: Users can set starting and ending points to find the solution to any maze currently displayed on the screen. The solution is displayed as a line passing through the middle of all cells in the maze through which the solution runs.

## Building and Installation

``
make install
``

The program includes a Makefile with standard targets for building and installing the application. The installation directory can be specified during installation, and the program can be easily uninstalled using the provided targets.

## Unit Tests

``make test``

The generation of perfect mazes and maze-solving modules are fully covered with unit tests to ensure the correctness and robustness of the implementation.

## Usage

`` make run ``

- Use Left Click to choose **Start point**
- Use Right Click to choose **End point**

## Gameplay

### Common gameplay

![common-gameplay.gif](dvi-folder/media/common-gameplay.gif)

### Scary gameplay

![scary-gameplay.gif](dvi-folder/media/scary-gameplay.gif)
