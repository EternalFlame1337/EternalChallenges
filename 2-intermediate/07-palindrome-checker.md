# Palindrome Checker

**Difficulty:** Intermediate

**Concepts:** Strings, String Manipulation, Comparison, Cleaning Input

---

## Description

Create a program that checks if a word or phrase is a palindrome (reads the same forwards and backwards).

Examples of palindromes:
- "racecar"
- "A man a plan a canal Panama"
- "Was it a car or a cat I saw"

---

## Requirements

- Ask the user to enter a word or phrase
- Check if it's a palindrome
- When checking phrases:
  - Ignore spaces
  - Ignore capitalization
  - Ignore punctuation (optional but recommended)
- Display whether it's a palindrome or not

---

## Example

*Lines starting with `>` represent user input.*

```
Enter a word or phrase:
> racecar
"racecar" is a palindrome!
```

```
Enter a word or phrase:
> hello
"hello" is not a palindrome.
```

```
Enter a word or phrase:
> A man a plan a canal Panama
"A man a plan a canal Panama" is a palindrome!
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

First "clean" the input: convert to lowercase and remove spaces (and optionally punctuation).

</details>

<details>
<summary>Hint 2</summary>

Reverse the cleaned string and compare it to the original cleaned string. If they're equal, it's a palindrome.

</details>

<details>
<summary>Hint 3</summary>

Alternatively, compare characters from the start and end moving inward. If all pairs match, it's a palindrome.

</details>

---

## Bonus Challenges

- [ ] Handle numbers as palindromes too (e.g., 12321)
- [ ] Find the longest palindrome in a sentence
- [ ] Suggest how to make a non-palindrome into one
- [ ] Check for "almost palindromes" (off by one character)
