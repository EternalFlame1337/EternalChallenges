# Mad Libs

**Difficulty:** Intermediate

**Concepts:** Strings, User Input, String Formatting/Replacement, Templates

---

## Description

Create a Mad Libs game where you ask the user for various words (nouns, verbs, adjectives, etc.) and then insert them into a story template to create a silly story.

---

## Requirements

- Have a story template with blanks for words
- Ask the user for each type of word needed (noun, verb, adjective, etc.)
- Fill in the blanks with their answers
- Display the complete silly story

---

## Example

*Lines starting with `>` represent user input.*

```
Let's play Mad Libs!

Enter a noun:
> elephant
Enter an adjective:
> sparkly
Enter a verb (past tense):
> danced
Enter another noun:
> pizza
Enter an adverb:
> enthusiastically

Here's your story:

The sparkly elephant danced enthusiastically into the room.
Everyone stopped and stared at the pizza in amazement.
It was the most memorable day anyone could remember!
```

---

## Sample Story Template

"The [adjective] [noun] [verb-past-tense] [adverb] into the room.
Everyone stopped and stared at the [noun] in amazement.
It was the most [adjective] day anyone could remember!"

(Create your own story or use this one!)

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Store your story template as a string with placeholder markers (like {NOUN1} or __NOUN__).

</details>

<details>
<summary>Hint 2</summary>

Most languages have string replacement functions. Replace each placeholder with the user's word.

</details>

<details>
<summary>Hint 3</summary>

Alternatively, break your story into pieces and concatenate them with the user's words between them.

</details>

---

## Bonus Challenges

- [ ] Create multiple story templates and let the user choose
- [ ] Load story templates from files
- [ ] Let users create their own templates
- [ ] Save completed stories to a file
- [ ] Add word type hints (e.g., "noun - a person, place, or thing")
