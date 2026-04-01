# Dice Roller

**Difficulty:** Intermediate

**Concepts:** Random Numbers, Loops, Input Parsing, Statistics

---

## Description

Create a dice rolling simulator that can handle different types of dice and multiple rolls, like those used in tabletop games.

---

## Requirements

- Ask the user what dice to roll (e.g., "2d6" means roll 2 six-sided dice)
- Generate random results for each die
- Display individual rolls and the total
- Handle common dice: d4, d6, d8, d10, d12, d20

---

## Dice Notation

Tabletop games use notation like "2d6":
- The number before 'd' = how many dice to roll
- The number after 'd' = how many sides on each die
- "3d8" = roll 3 eight-sided dice
- "1d20" = roll 1 twenty-sided die

---

## Example

*Lines starting with `>` represent user input.*

```
Enter dice to roll (e.g., 2d6):
> 2d6
Rolling 2d6...
Roll 1: 4
Roll 2: 6
Total: 10
```

```
Enter dice to roll (e.g., 2d6):
> 3d8
Rolling 3d8...
Roll 1: 7
Roll 2: 2
Roll 3: 5
Total: 14
```

```
Enter dice to roll (e.g., 2d6):
> 1d20
Rolling 1d20...
Roll 1: 17
Total: 17
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Parse the input by splitting on 'd'. The first part is the number of dice, the second is the sides per die.

</details>

<details>
<summary>Hint 2</summary>

For each die, generate a random number between 1 and the number of sides.

</details>

<details>
<summary>Hint 3</summary>

Keep a running total as you roll each die.

</details>

---

## Bonus Challenges

- [ ] Support modifiers like "2d6+5" (add 5 to total)
- [ ] Roll multiple different dice at once: "2d6 + 1d8 + 3"
- [ ] Show statistics: roll many times and show average, min, max
- [ ] Add "advantage" and "disadvantage" (roll twice, take higher/lower)
- [ ] Detect and celebrate critical rolls (max or min values)
