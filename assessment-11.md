# Assignment 11

## Assignment Description

Develop a "Number Guessing Game" that asks users to guess a number generated randomly between 0 and 100. This Game is multiplayer (One player will play at one time), so the Game must ask the user to enter the number of players to play game. At the End, the game will announce the first three winners based on the number of attempts made by each player. The player who will guess the game in less attempts will take first position. If there are more than one player who guessed in same attempts, they will be declared joint winner. But no more than three winners will be announced.

### For Random Number Generation

To generate random numbers in JavaScript, use:

```javascript
let guess = Math.floor(Math.random() * 100);
```

### Requirements

The game must be built in JavaScript based on the concepts discussed in class.

- At the Start of the Game, the Game will ask about the number of Players. So you must have to use a Data type that can hold score of more than one player. In this case you will use one dimensional Array. The index of the array will be used to identify a player.
- Game will start with Player1
- Game will allow each player to guess a number in 5 attempts
- Game will guide player by telling whether his guessed number is too low or too high so he may move towards a correct guess
- Once a player guess a correct number or complete his attempts the game will start with the next player
- Before starting with next player the game will generate a new random number for next player
- Every player's number of attempts will be stored with his index value that represents player number
- At the End Game will present a summary:

  ```md
  Total Player : 05
  Total Winners (Who guessed Number) : 02
  Total Looser : 03
  Top Three Winners : Player 4 , Player 2
  ```
