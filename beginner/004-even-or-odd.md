# Even or Odd

**Difficulty:** Beginner

**Concepts:** Variables, User Input, Conditionals (if/else), Modulo Operator

---

## Description

Create a program that determines whether a number is even or odd.

This challenge introduces you to:
- Making decisions with if/else statements
- The modulo operator (%) which gives you the remainder of division
- Comparing values to make decisions

---

## How It Works

A number is **even** if it's divisible by 2 with no remainder (0, 2, 4, 6, 8, 10...).
A number is **odd** if dividing by 2 leaves a remainder of 1 (1, 3, 5, 7, 9, 11...).

The **modulo operator** (`%`) gives you the remainder after division:
- `10 % 2 = 0` (10 ÷ 2 = 5 with remainder 0) → Even
- `7 % 2 = 1` (7 ÷ 2 = 3 with remainder 1) → Odd

---

## Requirements

- Ask the user to enter a number
- Determine if the number is even or odd
- Display the result

---

## Example

*Lines starting with `>` represent user input.*

```
Enter a number:
> 7
7 is odd!
```

```
Enter a number:
> 24
24 is even!
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Use the modulo operator `%` to find the remainder when dividing by 2.

</details>

<details>
<summary>Hint 2</summary>

If `number % 2` equals 0, the number is even. Otherwise, it's odd.

</details>

---

## Bonus Challenges

- [ ] Handle negative numbers
- [ ] Check multiple numbers in a loop until the user types "quit"
- [ ] Also tell the user if the number is divisible by 3, 5, or 10
