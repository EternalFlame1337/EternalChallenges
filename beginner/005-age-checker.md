# Age Checker

**Difficulty:** Beginner

**Concepts:** Variables, User Input, Conditionals, Comparison Operators

---

## Description

Create a program that asks for the user's age and gives them different messages based on their age group.

This challenge introduces you to:
- Comparing numbers using operators like `<`, `>`, `>=`, `<=`
- Using multiple conditions (if/else if/else)
- Making decisions based on ranges of values

---

## Requirements

- Ask the user to enter their age
- Display a different message based on their age:
  - Under 13: "You're a kid!"
  - 13-17: "You're a teenager!"
  - 18-64: "You're an adult!"
  - 65 and over: "You're a senior!"

---

## Example

*Lines starting with `>` represent user input.*

```
How old are you?
> 8
You're a kid!
```

```
How old are you?
> 16
You're a teenager!
```

```
How old are you?
> 30
You're an adult!
```

```
How old are you?
> 70
You're a senior!
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Use comparison operators: `<` (less than), `>` (greater than), `>=` (greater than or equal), `<=` (less than or equal).

</details>

<details>
<summary>Hint 2</summary>

Chain your conditions from lowest to highest (or highest to lowest) using if/else if/else.

</details>

<details>
<summary>Hint 3</summary>

You can combine conditions: "13 to 17" means `age >= 13` AND `age <= 17`. Some languages let you write this as `13 <= age <= 17`.

</details>

---

## Bonus Challenges

- [ ] Add more age categories (toddler, young adult, middle-aged, etc.)
- [ ] Calculate and display how many years until they reach the next category
- [ ] Handle invalid input (negative ages, non-numbers)
