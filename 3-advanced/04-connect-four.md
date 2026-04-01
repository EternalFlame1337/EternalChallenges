# Connect Four

**Difficulty:** Advanced

**Concepts:** 2D Arrays, Gravity Simulation, Win Detection, Game State, Complex Logic

---

## Description

Create a two-player Connect Four game. Players take turns dropping colored discs into a vertical grid. The first player to get four of their discs in a row (horizontally, vertically, or diagonally) wins.

---

## Requirements

- Display a 7-column by 6-row grid
- Players take turns (Red and Yellow, or X and O)
- Player chooses which column to drop their disc into
- Disc falls to the lowest available position in that column
- Detect win conditions:
  - 4 in a row horizontally
  - 4 in a row vertically
  - 4 in a row diagonally (both directions)
- Detect draw (board full, no winner)
- Prevent dropping into full columns

---

## Example

*Lines starting with `>` represent user input.*

```
| 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |
-----------------------------

Player R, choose a column (1-7):
> 4

| 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |
|   |   |   | R |   |   |   |
-----------------------------

Player Y, choose a column (1-7):
> 4

| 1 | 2 | 3 | 4 | 5 | 6 | 7 |
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |
|   |   |   | Y |   |   |   |
|   |   |   | R |   |   |   |
-----------------------------

...
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Store the board as a 2D array. When a disc is dropped, scan from the bottom of that column upward to find the first empty cell.

</details>

<details>
<summary>Hint 2</summary>

For win detection, after each move, check all four directions from the newly placed disc: horizontal, vertical, and both diagonals.

</details>

<details>
<summary>Hint 3</summary>

To check a direction, count consecutive matching discs in both directions from the placed disc. If the total (including the placed disc) is 4 or more, it's a win.

</details>

---

## Bonus Challenges

- [ ] Add an AI opponent with different difficulty levels
- [ ] Highlight the winning four discs
- [ ] Add an undo move feature
- [ ] Keep track of wins across multiple games
- [ ] Add animations (disc falling effect with delays)
