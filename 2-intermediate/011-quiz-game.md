# Quiz Game

**Difficulty:** Intermediate

**Concepts:** Arrays/Lists, Loops, Conditionals, Data Structures, Scoring

---

## Description

Create an interactive quiz game with multiple questions, answer checking, and score tracking.

This challenge teaches:
- Organizing related data (questions and answers)
- Iterating through data structures
- Tracking state across multiple rounds

---

## Requirements

- Store at least 5 questions with their correct answers
- Display each question one at a time
- Accept the user's answer and check if it's correct
- Track how many they got right
- At the end, display their score and percentage

---

## Example

*Lines starting with `>` represent user input.*

```
Welcome to the Quiz Game!

Question 1: What is the capital of France?
> Paris
Correct!

Question 2: What year did World War II end?
> 1945
Correct!

Question 3: What is the largest planet in our solar system?
> Saturn
Wrong! The answer was Jupiter.

Question 4: Who wrote Romeo and Juliet?
> Shakespeare
Correct!

Question 5: What is the chemical symbol for gold?
> Au
Correct!

Quiz Complete!
You scored 4 out of 5 (80%)
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Store questions and answers together. You could use parallel arrays (one for questions, one for answers), or a list of objects/dictionaries where each contains both.

</details>

<details>
<summary>Hint 2</summary>

Make answer checking case-insensitive by converting both the expected answer and user input to lowercase before comparing.

</details>

<details>
<summary>Hint 3</summary>

Keep a score counter that starts at 0 and increases by 1 for each correct answer.

</details>

---

## Bonus Challenges

- [ ] Add multiple choice options (a, b, c, d)
- [ ] Randomize the order of questions
- [ ] Add different categories of questions
- [ ] Include a timer for each question
- [ ] Store high scores to a file
- [ ] Support multiple correct answers for a question
