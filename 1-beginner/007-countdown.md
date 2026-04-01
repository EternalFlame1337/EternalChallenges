# Countdown

**Difficulty:** Beginner

**Concepts:** Loops, Variables, Counting, Output

---

## Description

Create a program that counts down from a number to zero, like a rocket launch countdown.

This challenge introduces you to:
- Loops (repeating code multiple times)
- Counting/incrementing variables
- Loop termination (when to stop)

---

## Requirements

- Ask the user for a starting number
- Count down from that number to 0
- Display each number as you count
- Display a final message when you reach 0 (like "Liftoff!" or "Blast off!")

---

## Example

*Lines starting with `>` represent user input.*

```
Enter the countdown start:
> 5
5
4
3
2
1
0
Liftoff!
```

```
Enter the countdown start:
> 3
3
2
1
0
Blast off!
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

You can use a `while` loop that continues as long as your counter is greater than or equal to 0.

</details>

<details>
<summary>Hint 2</summary>

Decrease your counter by 1 each time through the loop (e.g., `counter = counter - 1` or `counter -= 1` or `counter--`).

</details>

<details>
<summary>Hint 3</summary>

Many languages have a `for` loop that can count down: look up how to specify a negative step/increment.

</details>

---

## Bonus Challenges

- [ ] Add a 1-second delay between each number (look up "sleep" or "delay" in your language)
- [ ] Let the user choose what message to display at the end
- [ ] Count down in increments other than 1 (e.g., by 2s or 5s)
