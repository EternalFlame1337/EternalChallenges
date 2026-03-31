# Color Guesser

**Difficulty:** Beginner

**Concepts:** Variables, Loops, Conditionals, Sequential Validation

---

## Description

Create a guessing game where the user must guess your 3 favorite colors in the correct order. If they get any wrong, they start over from the beginning.

---

## Requirements

- Store 3 "secret" colors in your program
- Ask the user to guess each color one at a time, in order
- If they guess wrong at any point, restart from the first color
- If they guess all 3 correctly in a row, congratulate them
- Keep going until they succeed

---

## Example

*Lines starting with `>` represent user input.*

```
Guess my top 3 colors in order!
What's your first guess?
> Red
Yep! How about the second color?
> Blue
WRONG. Try again...

Guess my top 3 colors in order!
What's your first guess?
> Red
Yep! How about the second color?
> Green
Yep! How about the third color?
> Yellow
WOW CONGRATS YOU GOT THEM ALL!
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Use a loop that restarts whenever a wrong guess is made.

</details>

<details>
<summary>Hint 2</summary>

You can use a flag variable to track if they've failed, or use break/continue statements.

</details>

---

## Bonus Challenges

- [ ] Make the comparison case-insensitive (accept "red", "RED", "Red")
- [ ] Track and display how many attempts it took
- [ ] Randomly select the secret colors from a larger list
