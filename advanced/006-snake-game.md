# Snake Game

**Difficulty:** Advanced

**Concepts:** Game Loop, Collision Detection, Growing Data Structures, Timing, Input Handling

---

## Description

Create the classic Snake game! Control a snake that moves around the screen, eating food to grow longer. The game ends if the snake hits a wall or its own body.

**Note:** This challenge may require platform-specific libraries for real-time input and screen clearing. Some languages make this easier than others.

---

## Requirements

- Display a game board with borders
- Snake starts small (1-3 segments) and moves in a direction
- Player controls direction with keys (WASD or arrow keys)
- Food appears randomly on the board
- When snake eats food:
  - Snake grows by one segment
  - New food appears elsewhere
  - Score increases
- Game ends when snake:
  - Hits a wall, OR
  - Hits its own body
- Display score at the end

---

## Example

```
Score: 3

####################
#                  #
#                  #
#        @         #
#                  #
#    ooo>          #
#                  #
#                  #
####################

Use WASD to move. Press Q to quit.
```

Where:
- `#` = wall
- `>`, `<`, `^`, `v` = snake head (shows direction)
- `o` = snake body
- `@` = food

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Store the snake as a list of coordinates. The first element is the head. To move, add a new head position and remove the tail (unless eating).

</details>

<details>
<summary>Hint 2</summary>

The game loop: 1) Get input 2) Update snake position 3) Check collisions 4) Redraw screen 5) Wait briefly 6) Repeat.

</details>

<details>
<summary>Hint 3</summary>

For collision detection: check if the new head position matches any wall coordinate or any body segment coordinate.

</details>

<details>
<summary>Hint 4</summary>

Real-time input without pressing Enter is tricky. Look up "non-blocking input" or "getch" for your language. Alternatively, make it turn-based where each input moves the snake once.

</details>

---

## Simplified Version

If real-time input is too complex, make a turn-based version:
- Each time the user presses a direction key and Enter, the snake moves one step
- This is easier to implement while still teaching the core concepts

---

## Bonus Challenges

- [ ] Add increasing speed as the snake grows
- [ ] Add high score tracking with file persistence
- [ ] Add obstacles that appear over time
- [ ] Add multiple food types with different point values
- [ ] Implement wrap-around walls (snake appears on opposite side)
