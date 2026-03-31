# PIN Checker

**Difficulty:** Beginner

**Concepts:** Variables, Loops, Conditionals, User Input, Comparison

---

## Description

Create a simple PIN verification system. The program has a secret PIN stored, and the user must keep guessing until they enter the correct one.

---

## Requirements

- Store a secret PIN in your program (e.g., "1234")
- Ask the user to enter the PIN
- If incorrect, display an error and ask again
- If correct, grant access and end the program
- Keep looping until they get it right

---

## Example

*Lines starting with `>` represent user input.*

```
Please input the PIN:
> 0000
That is not the correct PIN. Please try again.
> 9999
That is not the correct PIN. Please try again.
> 1234
Correct! You have gained access to The Bank.
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Use a while loop that continues as long as the input doesn't match the PIN.

</details>

<details>
<summary>Hint 2</summary>

Compare the user's input directly to your stored PIN using equality.

</details>

---

## Bonus Challenges

- [ ] Limit the number of attempts (e.g., 3 tries then lockout)
- [ ] Add a "forgot PIN" option
- [ ] Hide the PIN input (show asterisks instead of characters)
