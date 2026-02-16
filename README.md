# Minefield - C Console Game

A console-based Minefield (Minesweeper-style) game written in C.

## Overview

This project is a simple implementation of the classic Minefield game.
The game runs in the terminal and allows the user to select coordinates
to reveal cells while avoiding hidden mines.

## Features

- Random mine placement
- User input for coordinates
- Win / lose condition detection
- Console-based interface
- Simple and clean C structure

## Requirements

- GCC or any C compiler
- Windows / Linux / macOS

## Build Instructions

Using GCC:

gcc main.c -o minefield

## Run

Windows:
minefield.exe

Linux / macOS:
./minefield

## Project Structure

main.c            -> Core game logic  
Makefile.win      -> Dev-C++ build configuration  

## Branch Strategy

main      -> Stable production branch  
develop   -> Development branch  
feature/* -> Feature branches  

## Future Improvements

- Difficulty levels
- Timer system
- Score tracking
- Improved UI formatting

## License

This project was developed for educational purposes.
