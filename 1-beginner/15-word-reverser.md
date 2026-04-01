# Word Reverser

**Difficulty:** Beginner

**Concepts:** Strings, Loops, Building Strings, Indexing

---

## Description

Create a program that takes a word and displays it reversed (spelled backwards).

This challenge teaches:
- Accessing individual characters in a string
- Building a new string character by character
- Looping through strings forwards or backwards

---

## How It Works

"hello" reversed becomes "olleh"
"Python" reversed becomes "nohtyP"

You can do this by:
- Starting with an empty result string
- Going through the original string and adding each character to the FRONT of your result
- OR going through the string backwards and adding each character to the END

---

## Requirements

- Ask the user to enter a word
- Reverse the word
- Display the reversed word

---

## Example

*Lines starting with `>` represent user input.*

```
Enter a word:
> hello
Reversed: olleh
```

```
Enter a word:
> Programming
Reversed: gnimmargorP
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Start with an empty string for your result. Loop through the original word and add each character to the BEGINNING of your result string.

</details>

<details>
<summary>Hint 2</summary>

Alternatively, loop through the word backwards (from the last character to the first) and add each to the END of your result.

</details>

<details>
<summary>Hint 3</summary>

Many languages have built-in ways to reverse strings, but try doing it manually with a loop first to understand the concept!

</details>

---

## Bonus Challenges

- [ ] Reverse a full sentence but keep the words in order ("hello world" → "olleh dlrow")
- [ ] Reverse the word order in a sentence ("hello world" → "world hello")
- [ ] Check if a word is a palindrome (same forwards and backwards)
