# Hangman

**Difficulty:** Advanced

**Concepts:** Strings, Arrays/Lists, Loops, Conditionals, Game State, ASCII Art (optional)

---

## Description

Create the classic Hangman word-guessing game. One player sets a secret word, and the other player tries to guess it letter by letter before running out of attempts.

---

## Requirements

- Ask for a secret word to be guessed (or have a built-in word)
- Display the word as underscores/blanks initially (e.g., "_ _ _ _ _")
- Let the player guess one letter at a time
- Reveal correctly guessed letters in their positions
- Track and display wrong guesses
- Track remaining attempts (typically 6-7 wrong guesses allowed)
- End the game when:
  - The word is fully guessed (win)
  - The player runs out of attempts (lose)

---

## Example

*Lines starting with `>` represent user input.*

```
The secret word has been set!

Word: _ _ _ _ _
Wrong guesses: (none)
Attempts remaining: 6

Guess a letter:
> e

Word: _ e _ _ _
Wrong guesses: (none)
Attempts remaining: 6

Guess a letter:
> a

Wrong! 'a' is not in the word.

Word: _ e _ _ _
Wrong guesses: a
Attempts remaining: 5

Guess a letter:
> h

Word: h e _ _ _
Wrong guesses: a
Attempts remaining: 5

...

Word: h e l l o
Congratulations! You guessed the word!
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Keep track of the secret word and a separate "display" version that shows guessed letters and blanks.

</details>

<details>
<summary>Hint 2</summary>

Use a list or string to track all the letters that have been guessed.

</details>

<details>
<summary>Hint 3</summary>

When a correct letter is guessed, loop through the secret word and reveal all occurrences of that letter.

</details>

---

## Bonus Challenges

- [ ] Draw ASCII art of the hangman as wrong guesses accumulate
- [ ] Add a word list and randomly select the secret word
- [ ] Prevent guessing the same letter twice
- [ ] Add difficulty levels (fewer attempts, longer words)
- [ ] Support phrases with spaces
