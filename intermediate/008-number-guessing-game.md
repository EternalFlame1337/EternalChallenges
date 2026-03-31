# Number Guessing Game

**Difficulty:** Intermediate

**Concepts:** Random Numbers, Loops, Conditionals, Input Validation, Game Logic

---

## Description

Create a complete number guessing game where the computer picks a random secret number and the player tries to guess it with hints along the way.

This builds on basic concepts by adding:
- Random number generation
- Game loop with win/lose conditions
- Attempt tracking and limits

---

## Requirements

- Generate a random number between 1 and 100
- Give the player a limited number of guesses (e.g., 7 attempts)
- After each guess, tell them if they're too high or too low
- If they guess correctly, congratulate them and show how many attempts they used
- If they run out of guesses, reveal the answer
- Ask if they want to play again

---

## Example

*Lines starting with `>` represent user input.*

```
I'm thinking of a number between 1 and 100.
You have 7 attempts. Good luck!

Attempt 1/7 - Enter your guess:
> 50
Too low! Try higher.

Attempt 2/7 - Enter your guess:
> 75
Too high! Try lower.

Attempt 3/7 - Enter your guess:
> 62
Too low! Try higher.

Attempt 4/7 - Enter your guess:
> 68
Correct! You got it in 4 attempts!

Play again? (yes/no)
> no
Thanks for playing!
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Most languages have a random library. You typically need to import it and then generate a number in a range (e.g., `random.randint(1, 100)` in Python).

</details>

<details>
<summary>Hint 2</summary>

Use a while loop that continues while: guesses remaining > 0 AND they haven't won yet.

</details>

<details>
<summary>Hint 3</summary>

Wrap the entire game in another loop if you want the "play again" feature.

</details>

---

## Bonus Challenges

- [ ] Add difficulty levels that change the range and number of guesses
- [ ] Track high scores (fewest guesses to win)
- [ ] Give hints like "You're getting warmer!" based on distance from answer
- [ ] Add a "give up" option that reveals the answer
