# Sum of Numbers

**Difficulty:** Beginner

**Concepts:** Loops, Accumulator Pattern, Variables, Math

---

## Description

Create a program that calculates the sum of all numbers from 1 to a number the user provides.

This challenge introduces:
- The "accumulator" pattern (adding to a running total)
- Using a variable to track a value across loop iterations
- Building up a result piece by piece

---

## How It Works

If the user enters 5, you calculate: 1 + 2 + 3 + 4 + 5 = 15

You do this by keeping a "running total" that starts at 0, then adding each number as you loop through them.

---

## Requirements

- Ask the user for a positive number
- Calculate the sum of all numbers from 1 to that number
- Display the result

---

## Example

*Lines starting with `>` represent user input.*

```
Enter a number:
> 5
The sum of numbers from 1 to 5 is: 15
```

```
Enter a number:
> 10
The sum of numbers from 1 to 10 is: 55
```

```
Enter a number:
> 100
The sum of numbers from 1 to 100 is: 5050
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Create a variable called `sum` or `total` and set it to 0 before your loop starts.

</details>

<details>
<summary>Hint 2</summary>

Inside your loop, add the current number to your total: `total = total + currentNumber`

</details>

<details>
<summary>Hint 3</summary>

Your loop should count from 1 up to (and including) the number the user entered.

</details>

---

## Bonus Challenges

- [ ] Also display the formula (e.g., "1 + 2 + 3 + 4 + 5 = 15")
- [ ] Let the user specify a start and end number (e.g., sum from 5 to 10)
- [ ] Calculate the average of the numbers as well
