# HangmanInCPP

This repository hosts the source code for a Hangman game implemented in C++. The game is a popular word-guessing game where the player tries to figure out a hidden word by guessing letters. If the player guesses too many incorrect letters, the hangman gets "hanged," and the game ends. This implementation is structured across three main files to organize functionality and provide a clear separation of logic and interface.

# File Structure
- main.cpp: Contains the main game loop and is responsible for interacting with the user.
- hangman_fonctions.h: Header file declaring all functions used for the Hangman game logic.
- hangman_fonctions.cpp: Implementation of the functions declared in hangman_fonctions.h. This includes logic for choosing a word, checking guesses, and updating the game state.

# Installation
1. Clone the Repository
```
git clone https://github.com/AFP17/HangmanInCPP.git
```
2. Navigate to the Project Directory
```
cd HangmanInCPP
```
3. Compile the Project

g++ -std=c++17 -o Hangman main.cpp hangman_fonctions.cpp

Run the Application
bash
Copy code
./Hangman
Usage
Start the game by running the executable. The game will prompt you to guess letters to try and figure out the hidden word. Input your guesses according to the prompts.

Contributing
Contributions are welcome, and any improvements or suggestions are greatly appreciated.

Fork the project.
Create your feature branch (git checkout -b feature/CoolFeature).
Commit your changes (git commit -m 'Add some CoolFeature').
Push to the branch (git push origin feature/CoolFeature).
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Acknowledgments
Hat tip to anyone whose code was used.
Inspiration.
etc.