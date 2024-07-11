# 2048 Game

2048 is a single-player sliding block puzzle game. The game's objective is to slide numbered tiles on a grid to combine them to create a tile with the number 2048.

## Demo

[DEMO LINK](https://antypenko-bohdan.github.io/js_2045_game/)

## Technologies used

* HTML5
* CSS3
* Sass (SCSS)
* JavaScript

## Game logic

* The game field is 4 x 4 (16 cells)
* Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
* The game starts with 2 cells filled with 2 or 4
* The game can be started by clicking the `Start` button
* The player can move cells with keyboard arrows
* All the numbers are moved in the selected direction until all empty cells are filled in
   * 2 equal cells are merged into a doubled number
   * The merged cell can't be merged twice during one move
* The move is possible if at least one cell is changed after the move
* After move 2 or 4 appears in a random empty cell. 4 probability is 10%
* When `2048` value is displayed in any cell, win message will be shown
* The `game over` message will be shown if there are no more available moves
* Score is increased by the sum of all merged cells
* The game can be restarted by clicking the `Restart` button

## How to run the project locally

* Fork and clone this repository
* Run `npm install` in your terminal
* Run `npm start` to start the project locally
* Open `http://localhost:8080/` in your browser

## Dependencies

* Node.js
* npm

## Project Structure

* `index.html`: The main HTML file
* `styles/main.scss`: SCSS file for styling
* `scripts/main.js`: Main JavaScript file for game logic
* `modules/Game.class.js`: Game class definition

## Reflections

This project focuses on implementing the classic 2048 game using JavaScript, HTML, and CSS. It provides an opportunity to practice DOM manipulations and combine front-end technologies to create an interactive game.

The main challenge lies in implementing the game logic, considering all possible scenarios and implementing them effectively. This project serves as a practical exercise in building complex logic using fundamental web development skills.

This implementation is inspired by the original 2048 game.
