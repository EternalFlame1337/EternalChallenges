# Grade Calculator

**Difficulty:** Beginner

**Concepts:** Variables, User Input, Multiple Conditionals, Number Ranges

---

## Description

Create a program that converts a numerical score (0-100) into a letter grade.

This challenge practices:
- Checking which range a number falls into
- Using multiple if/else if conditions
- Handling boundary cases (what happens at exactly 90?)

---

## Requirements

- Ask the user to enter their score (0-100)
- Convert the score to a letter grade:
  - 90-100: A
  - 80-89: B
  - 70-79: C
  - 60-69: D
  - Below 60: F
- Display the letter grade

---

## Example

*Lines starting with `>` represent user input.*

```
Enter your score (0-100):
> 85
Your grade is: B
```

```
Enter your score (0-100):
> 92
Your grade is: A
```

```
Enter your score (0-100):
> 58
Your grade is: F
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Start checking from the highest grade down, or lowest up. Be careful about boundary values (is 90 an A or a B?).

</details>

<details>
<summary>Hint 2</summary>

You can simplify checks by using the order of conditions. If you check `score >= 90` first and it's false, you already know the score is less than 90 for all following checks.

</details>

---

## Bonus Challenges

- [ ] Add +/- grades (A+, A, A-, B+, etc.)
- [ ] Handle invalid scores (negative or over 100)
- [ ] Calculate the grade for multiple scores and show an average
- [ ] Let the user customize the grade boundaries
