# Number Guesser (Simple)

**Difficulty:** Beginner

**Concepts:** Loops, Conditionals, Comparison, User Input

---

## Description

Create a simple number guessing game where the program has a secret number and the player tries to guess it.

This challenge combines:
- A loop that continues until something happens
- Comparing user input to a target value
- Giving feedback based on comparisons

---

## Requirements

- Store a secret number in your program (e.g., 7)
- Ask the player to guess the number
- Tell them if their guess is too high, too low, or correct
- Keep asking until they guess correctly
- When they win, tell them how many guesses it took

---

## Example

*Lines starting with `>` represent user input.*

```
I'm thinking of a number between 1 and 10. Can you guess it?
> 5
Too low! Try again.
> 8
Too high! Try again.
> 7
Correct! You got it in 3 guesses!
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Use a while loop that continues as long as the guess doesn't equal the secret number.

</details>

<details>
<summary>Hint 2</summary>

Keep a counter variable that increases by 1 each time the player guesses.

</details>

<details>
<summary>Hint 3</summary>

Use if/else if/else to check: is the guess greater than, less than, or equal to the secret?

</details>

---

## Bonus Challenges

- [ ] Generate a random secret number instead of hardcoding it
- [ ] Limit the number of guesses allowed
- [ ] Let the player choose the difficulty (1-10, 1-100, 1-1000)
- [ ] Add a "play again" option when they finish
