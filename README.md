JS GAME "2048"

2048 is a single-player sliding block puzzle game. The game’s objective is to slide numbered tiles on a grid to combine them to create a tile with the number 2048. The project was developed on the basis of the training course "Mate Academy".

DEMO LINK - https://NikaNika12.github.io/2048-js-game/

GITHUB REPOSITORY LINK - https://github.com/NikaNika12/2048-js-game

Installing and running the project:

npm install
npm start

The rules of creating this game:

1. The game field is 4 x 4
2. Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
3. The player can move cells with keyboard arrows
4. All the numbers should be moved in the selected direction until all empty cells are filled in 2 equal cells should be merged into a doubled number
5. The merged cell can’t be merged twice during one move
6. The move is possible if at least one cell is changed after the move
7. After move 2 or 4 appears in a random empty cell. 4 probability is 10%
8. When 2048 value is displayed in any cell, win message should be shown.
9. The game over message should be shown if there are no more available moves.
10. Hide start message when game starts.
11. Change the Start button to Restart after the first move.
12. Increase score with each move. The score should be increased by the sum of all merged cells.

Technology stack:

HTML5,
CSS3 and SCSS preprocessor,
JavaScript.
