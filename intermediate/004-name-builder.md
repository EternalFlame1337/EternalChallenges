# Name Builder

**Difficulty:** Intermediate

**Concepts:** Conditionals, User Input, String Building, Boolean Logic

---

## Description

Create an interactive name collector that asks the user about each part of their name using yes/no questions. Only ask for details they confirm they have, and handle the case where they have no name at all.

---

## Requirements

- Ask if the user has a first name (Y/N)
  - If yes, ask what it is
- Ask if the user has a middle name (Y/N)
  - If yes, ask what it is
- Ask if the user has a last name (Y/N)
  - If yes, ask what it is
- At the end:
  - If they provided at least one name part, display their full name
  - If they said no to everything, tell them they have no name

---

## Example

*Lines starting with `>` represent user input.*

**Example with partial name:**
```
Hello there, do you happen to have a first name? (Y/N)
> N
Oh okay no worries.. how about a middle name? (Y/N)
> Y
What is it?
> SmorZ
And do you have a last name? (Y/N)
> Y
Great, what is it?
> Walker
Cool, so your full name is SmorZ Walker!
```

**Example with no name:**
```
Hello there, do you happen to have a first name? (Y/N)
> N
Oh okay no worries.. how about a middle name? (Y/N)
> N
And do you have a last name? (Y/N)
> N
You have no name!
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Use separate variables for each name part, initialized as empty strings.

</details>

<details>
<summary>Hint 2</summary>

When building the final name, only include parts that aren't empty.

</details>

<details>
<summary>Hint 3</summary>

Check if all name parts are empty to determine if they have "no name."

</details>

---

## Bonus Challenges

- [ ] Accept variations like "yes", "no", "y", "n" (case-insensitive)
- [ ] Handle invalid Y/N responses by asking again
- [ ] Add nickname support
