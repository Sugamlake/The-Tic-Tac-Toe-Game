# The-Tic-Tac-Toe-Game

### Description: 
Tic-tac-toe is a board game where by means of three equal marks in a diagonal direction or up and down and vice versa you can win. 

### Features: 
- A grill is made to give structure to the board
- The Board and the marks are painted with CSS3
- React and JSX are incorporated for:
- State keeps track of the next player and gameState
- Use conditional logic to set a variable to 'Player O' or 'Player X'
use properties to pass the takeTurn to Child callback function

  - id is the number of the square
  - Fill tells you if the square has been filled
  - tik tells you the symbol in the square (same as the player)
  - Call takeTurn to tell Parent that the square has been filled
Verifying the winner takes a bit of work
Use JavaScript sets to check player options
against winning combinations


### Improvements :

- The possible improvements to be implemented would be not allowing more entries by the players once they have won one.

- Also being able to store the number of games played and won.

- These improvements would be implemented by using useState to change the variables to check a winning game and count who has won the most games.

### Installation Guidelines: 
- First clone the project
- Initialize a web server as go live in the locations of the The-Tic-Tac-Toe-Game project
- The execution is by opening the index.html file in any browser, if you want to see it with a console I recommend Google Chrome; by pressing the "The-Tic-Tac-Toe-Game" button you will see the grid and play the game.

### Screenshots: 

[![Captura-de-Pantalla-2022-07-06-a-la-s-01-04-10.png](https://i.postimg.cc/2yD8NTKf/Captura-de-Pantalla-2022-07-06-a-la-s-01-04-10.png)](https://postimg.cc/R6gzc1mP)

### Technology used: 
- HTML5
- CSS3
- JavaScript
- React 
- JSX
- Boostrap


### MIT License

Copyright (c) [2021] [ Susana Gamboa Navarro]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
