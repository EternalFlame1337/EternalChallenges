# Tip Calculator

**Difficulty:** Beginner

**Concepts:** Variables, Math, User Input, Percentages, Formatted Output

---

## Description

Create a program that calculates the tip and total bill at a restaurant.

This is a practical, real-world application of:
- Percentage calculations
- Math operations
- Formatting money output

---

## Requirements

- Ask for the bill amount
- Ask for the tip percentage (or offer preset options like 15%, 18%, 20%)
- Calculate the tip amount
- Calculate the total (bill + tip)
- Display the results

---

## Example

*Lines starting with `>` represent user input.*

```
What was the bill amount?
> 45.50
What tip percentage would you like to leave?
> 20

Bill: $45.50
Tip (20%): $9.10
Total: $54.60
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

To calculate a percentage: `tip = bill * (percentage / 100)` or `tip = bill * percentage / 100`.

</details>

<details>
<summary>Hint 2</summary>

To display money properly, you may want to round to 2 decimal places. Look up how to format numbers in your language.

</details>

---

## Bonus Challenges

- [ ] Split the bill among multiple people
- [ ] Offer preset tip options (1 = 15%, 2 = 18%, 3 = 20%, 4 = custom)
- [ ] Round the total up to a nice number
- [ ] Show what each person owes when splitting
