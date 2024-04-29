# Hangman Game in C++

This repository contains a classic Hangman game implemented in C++. Hangman is a word-guessing game where players try to figure out an unknown word by guessing letters. For each incorrect guess, a part of the hangman is drawn. The goal is to guess the word before the hangman is fully drawn.

# File Structure
The project consists of the following files:

- main.cpp: The entry point of the game that handles the game loop and user interactions.
- hangman_functions.cpp: Contains the logic for the game's core functionalities, such as processing guesses and updating the game state.
- hangman_functions.h: Header file for declaring functions and including libraries needed by hangman_functions.cpp.

# Getting Started
These instructions will guide you through setting up the project on your local machine for development and testing purposes.

# Prerequisites
You need a C++ compiler that supports C++17. GCC or Clang are recommended. Ensure you have Git installed to clone the repository.

# Installation
1. Clone the Repository
```
git clone https://github.com/AFP17/HangmanInCPP.git
```
2. Go to the folder
```
cd HangmanInCPP
```
3. Compile the ProjectYou can compile the project manually using the following commands:
```
g++ -c main.cpp -o main.o
g++ -c hangman_functions.cpp -o hangman_functions.o
g++ main.o hangman_functions.o -o hangman
```
4. Run the ApplicationAfter compiling, you can start the game by running:
```
./hangman
```

# Usage
To play the game, run the executable and follow the on-screen instructions. The game will prompt you to guess letters to try and figure out the hidden word.

# Acknowledgments
- Inspiration from classic hangman games.
- This was made possible thanks to Coding Cleverly tutorial on Youtube. 