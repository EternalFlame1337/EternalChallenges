# Word Counter

**Difficulty:** Intermediate

**Concepts:** Strings, Splitting, Loops, Counting, Text Processing

---

## Description

Create a program that analyzes text and provides statistics about it: word count, character count, and more.

This challenge teaches:
- Splitting strings into parts
- Counting and accumulating
- Text processing techniques

---

## Requirements

- Ask the user to enter some text (a sentence or paragraph)
- Calculate and display:
  - Number of characters (including spaces)
  - Number of characters (excluding spaces)
  - Number of words
  - Number of sentences (count periods, question marks, exclamation points)

---

## Example

*Lines starting with `>` represent user input.*

```
Enter your text:
> Hello world! How are you doing today? I hope you are well.

Text Statistics:
Characters (with spaces): 59
Characters (no spaces): 49
Words: 12
Sentences: 3
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Most languages have a "split" function that breaks a string into a list of words by a delimiter (usually spaces).

</details>

<details>
<summary>Hint 2</summary>

To count characters without spaces, you can loop through each character and only count it if it's not a space. Or remove all spaces first and count the length.

</details>

<details>
<summary>Hint 3</summary>

For sentence count, loop through and count occurrences of `.`, `?`, and `!`.

</details>

---

## Bonus Challenges

- [ ] Find and display the longest word
- [ ] Find and display the most common word
- [ ] Calculate average word length
- [ ] Count paragraphs (separated by blank lines)
- [ ] Ignore multiple spaces between words
