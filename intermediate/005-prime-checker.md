# Prime Checker

**Difficulty:** Intermediate

**Concepts:** Loops, Conditionals, Math/Division, Algorithms

---

## Description

Create a program that determines whether a given number is prime or not. A prime number is only divisible by 1 and itself.

---

## Requirements

- Ask the user to input a number
- Determine if the number is prime
- Display the result

---

## What is a Prime Number?

A prime number is a number greater than 1 that has no divisors other than 1 and itself.

- **Prime:** 2, 3, 5, 7, 11, 13, 17, 19, 23...
- **Not prime:** 1, 4, 6, 8, 9, 10, 12, 14, 15...

---

## Example

*Lines starting with `>` represent user input.*

```
Enter a number:
> 17
17 is a prime number!
```

```
Enter a number:
> 24
24 is not a prime number.
```

```
Enter a number:
> 2
2 is a prime number!
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

A number is not prime if any number between 2 and itself minus 1 divides evenly into it.

</details>

<details>
<summary>Hint 2</summary>

Use the modulo operator (%) to check if a division has a remainder of 0.

</details>

<details>
<summary>Hint 3</summary>

You only need to check divisors up to the square root of the number for efficiency, but checking up to n-1 works fine for learning.

</details>

---

## Bonus Challenges

- [ ] Handle edge cases: negative numbers, 0, and 1
- [ ] Display what number it's divisible by if not prime
- [ ] Find and display all prime numbers up to the input number
