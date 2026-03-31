# Character Lister

**Difficulty:** Beginner

**Concepts:** Strings, Loops, Arrays/Lists, String Concatenation

---

## Description

Create a program that takes a phrase and breaks it down character by character, appending a suffix to each one and displaying the results.

---

## Requirements

- Ask the user for a phrase
- For each character in the phrase (including spaces and punctuation):
  - Add it to a list/array with "LOL" appended
- Display each item in the list

---

## Example

*Lines starting with `>` represent user input.*

```
Input a phrase and I'll do something to it:
> Okay..
OLOL
kLOL
aLOL
yLOL
.LOL
.LOL
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Loop through the string by index or use a for-each style loop to access each character.

</details>

<details>
<summary>Hint 2</summary>

Create an empty list first, then append each transformed character to it.

</details>

---

## Bonus Challenges

- [ ] Let the user choose what suffix to append (instead of hardcoding "LOL")
- [ ] Skip spaces instead of including them
- [ ] Display the results on a single line, separated by commas
