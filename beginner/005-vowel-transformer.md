# Vowel Transformer

**Difficulty:** Beginner

**Concepts:** Strings, Loops, Conditionals, Character Manipulation

---

## Description

Create a program that transforms text by making all vowels UPPERCASE and all consonants lowercase.

---

## Requirements

- Ask the user to input some text
- Transform the text so that:
  - All vowels (A, E, I, O, U) become uppercase
  - All other letters become lowercase
- Display the transformed result
- Non-letter characters (spaces, numbers, punctuation) stay unchanged

---

## Example

*Lines starting with `>` represent user input.*

```
Enter your text:
> Hello There
Result: hEllO thErE
```

Another example:
```
Enter your text:
> PROGRAMMING IS FUN
Result: prOgrAmmIng Is fUn
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Loop through each character in the string and check if it's a vowel.

</details>

<details>
<summary>Hint 2</summary>

Build a new string character by character, transforming each one as you go.

</details>

<details>
<summary>Hint 3</summary>

Check for both uppercase and lowercase vowels, or convert to one case first before checking.

</details>

---

## Bonus Challenges

- [ ] Also treat 'Y' as a vowel
- [ ] Count and display how many vowels were found
- [ ] Allow the user to choose: vowels uppercase OR consonants uppercase
