# Tic Tac Toe

**Difficulty:** Advanced

**Concepts:** 2D Arrays, Loops, Conditionals, Game Logic, Win Detection

---

## Description

Create a two-player Tic Tac Toe game. Players take turns placing their marks (X and O) on a 3x3 grid until someone wins or the game ends in a draw.

---

## Requirements

- Display a 3x3 game board
- Alternate turns between Player X and Player O
- Allow players to choose where to place their mark
- Prevent placing marks on already-occupied spaces
- Detect when a player wins (3 in a row: horizontal, vertical, or diagonal)
- Detect when the game ends in a draw (board full, no winner)
- Display the winner or draw result

---

## Example

*Lines starting with `>` represent user input.*

```
 1 | 2 | 3
-----------
 4 | 5 | 6
-----------
 7 | 8 | 9

Player X, choose a position (1-9):
> 5

 1 | 2 | 3
-----------
 4 | X | 6
-----------
 7 | 8 | 9

Player O, choose a position (1-9):
> 1

 O | 2 | 3
-----------
 4 | X | 6
-----------
 7 | 8 | 9

Player X, choose a position (1-9):
> 3

 O | 2 | X
-----------
 4 | X | 6
-----------
 7 | 8 | 9

...

Player X wins!
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Store the board as a list/array with 9 elements, or a 3x3 2D array.

</details>

<details>
<summary>Hint 2</summary>

To check for a win, check all 8 possible winning combinations: 3 rows, 3 columns, 2 diagonals.

</details>

<details>
<summary>Hint 3</summary>

Use a turn counter or boolean to track whose turn it is, flipping after each valid move.

</details>

---

## Bonus Challenges

- [ ] Add input validation (handle non-numbers, out of range)
- [ ] Keep score across multiple games
- [ ] Add a simple AI opponent for single-player mode
- [ ] Allow custom board sizes (4x4, 5x5)
