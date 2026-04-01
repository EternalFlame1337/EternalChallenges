# Fibonacci Generator

**Difficulty:** Intermediate

**Concepts:** Loops, Variables, Mathematical Sequences, Algorithms

---

## Description

Create a program that generates the Fibonacci sequence up to a certain point.

The Fibonacci sequence is a famous mathematical sequence where each number is the sum of the two numbers before it:
`0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, ...`

---

## How It Works

- Start with 0 and 1
- Each new number = previous number + the number before that
- 0 + 1 = 1
- 1 + 1 = 2
- 1 + 2 = 3
- 2 + 3 = 5
- And so on...

---

## Requirements

- Ask the user how many Fibonacci numbers to generate
- Generate and display that many numbers in the sequence
- Start from 0

---

## Example

*Lines starting with `>` represent user input.*

```
How many Fibonacci numbers would you like?
> 10
Fibonacci sequence:
0, 1, 1, 2, 3, 5, 8, 13, 21, 34
```

```
How many Fibonacci numbers would you like?
> 15
Fibonacci sequence:
0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, 377
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Keep track of two variables: the "previous" number and the "current" number. Each iteration, calculate the next number and shift the variables.

</details>

<details>
<summary>Hint 2</summary>

Handle the first two numbers (0 and 1) as special cases, or initialize your variables properly to handle them naturally.

</details>

<details>
<summary>Hint 3</summary>

You can also use an array/list to store all the numbers, which makes printing them easier.

</details>

---

## Bonus Challenges

- [ ] Generate Fibonacci numbers up to a maximum VALUE instead of a count
- [ ] Check if a given number IS a Fibonacci number
- [ ] Calculate the ratio between consecutive numbers (approaches the Golden Ratio!)
- [ ] Implement using recursion (but be careful with large numbers!)
