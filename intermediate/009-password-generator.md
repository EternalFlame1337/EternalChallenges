# Password Generator

**Difficulty:** Intermediate

**Concepts:** Random Selection, Strings, Loops, Arrays/Lists, String Building

---

## Description

Create a program that generates random, secure passwords based on user preferences.

This challenge involves:
- Randomly selecting characters from character sets
- Building strings dynamically
- Working with multiple character categories

---

## Requirements

- Ask the user how long they want the password
- Generate a random password of that length
- Use a mix of:
  - Lowercase letters (a-z)
  - Uppercase letters (A-Z)
  - Numbers (0-9)
  - Special characters (!@#$%^&*)
- Display the generated password

---

## Example

*Lines starting with `>` represent user input.*

```
How long should your password be?
> 12
Your generated password is: Kx7#mP2@nQz9
```

```
How long should your password be?
> 8
Your generated password is: aB3$fG7!
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Create strings containing all possible characters for each category, then combine them into one master string of all possible characters.

</details>

<details>
<summary>Hint 2</summary>

Loop for the number of characters needed, randomly picking one character each time and adding it to your result.

</details>

<details>
<summary>Hint 3</summary>

To pick a random character from a string, generate a random index between 0 and the length of the string minus 1.

</details>

---

## Bonus Challenges

- [ ] Let the user choose which character types to include (with checkboxes/options)
- [ ] Ensure at least one character from each selected category is included
- [ ] Generate multiple passwords at once
- [ ] Add an "easy to read" option that excludes confusing characters (0/O, 1/l/I)
- [ ] Calculate and display password strength
