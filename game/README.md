# Bootcamp Quest

Bootcamp Quest is an interactive game inspired by the classic Hangman. This README file provides information about the code, which includes HTML, JavaScript, and CSS to create the game.

## Table of Contents
- [Description](#description)
- [Setup](#setup)
- [Game Instructions](#game-instructions)
- [HTML Structure](#html-structure)
- [CSS Styles](#css-styles)
- [JavaScript Logic](#javascript-logic)

## Description
Bootcamp Quest is a web-based version of the classical Hangman game. In this game, players are challenged to guess a secret word related to programming topics such as HTML, CSS, or JavaScript. The game features a graphical representation of a bootcamp school building that progressively disintegrates as players make wrong guesses. Players have a limited number of tries to guess the word before the building completely falls appart.

## Setup
To run Bootcamp Quest, follow these steps:
1. Copy the provided code into an HTML file.
2. Save the HTML file with a .html extension.
3. Ensure that the HTML file and the required assets (images and stylesheets) are in the same directory.
4. Open the HTML file in a web browser.

## Game Instructions
1. When the game starts, players are prompted to select a category corresponding to a specific programming topic (HTML, CSS, or JavaScript).
2. The player clicks on a category button to choose a category.
3. Once a category is selected, the game generates a secret word from that category.
4. The secret word is displayed as a series of underscores representing the hidden letters.
5. the player guesses letters by clicking the letter buttons provided.
6. If a guessed letter is correct, the corresponding underscore(s) in the secret word are revealed.
7. If a guessed letter is incorrect, the house progressively disintegrates, and players have a limited number of tries to guess the word.
8. The game continues until the entire word is revealed or too many incorrect guesses are made.
9. Winning the game requires revealing the entire word.
10. Losing the game occurs when too many incorrect guesses are made.
11. After the game ends, players can start a new game by clicking the "New Game" button.

## HTML Structure
The HTML code includes elements such as categories buttons, the secret word display, the letter buttons, and the graphical representation of the disintegrating house.

## CSS Styles
The CSS code provides the visual styling for the game, including the appearance of buttons and the graphical elements of the disintegrating house.

## JavaScript Logic
The JavaScript code handles the game logic, including generating random words from selected categories, encrypting words with underscores, handling user guesses, updating the graphical representation of the house, and checking for win or loss conditions. The code also includes event listeners for button clicks and functions for starting a new game.

Please note that the provided code is a far from perfect and additional code may be required for full functionality.

Enjoy playing Bootcamp Quest, the web-based version of the classic Hangman game!
