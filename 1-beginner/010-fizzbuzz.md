# FizzBuzz

**Difficulty:** Beginner

**Concepts:** Loops, Conditionals, Modulo, Multiple Conditions

---

## Description

FizzBuzz is a classic programming challenge that combines loops and conditionals. Count from 1 to a number, but replace some numbers with words.

This challenge tests your understanding of:
- Loops and counting
- Checking multiple conditions
- The order conditions are checked matters!

---

## The Rules

For each number from 1 to N:
- If the number is divisible by 3, print "Fizz"
- If the number is divisible by 5, print "Buzz"
- If the number is divisible by BOTH 3 and 5, print "FizzBuzz"
- Otherwise, print the number itself

---

## Requirements

- Ask the user how high to count (or just count to 100)
- For each number, apply the FizzBuzz rules
- Display the results

---

## Example

*Lines starting with `>` represent user input.*

```
Count up to:
> 15

1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Use the modulo operator `%` to check divisibility. If `number % 3 == 0`, the number is divisible by 3.

</details>

<details>
<summary>Hint 2</summary>

**Order matters!** Check if the number is divisible by BOTH 3 AND 5 first, before checking each individually. Otherwise, you'll print "Fizz" or "Buzz" instead of "FizzBuzz".

</details>

<details>
<summary>Hint 3</summary>

A number is divisible by both 3 and 5 if `number % 3 == 0 AND number % 5 == 0`. Alternatively, you can check if it's divisible by 15.

</details>

---

## Bonus Challenges

- [ ] Add more rules (e.g., divisible by 7 = "Bazz")
- [ ] Let the user choose what numbers to check for
- [ ] Count how many Fizzes, Buzzes, and FizzBuzzes there were
