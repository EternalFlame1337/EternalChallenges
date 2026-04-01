# Text Adventure

**Difficulty:** Intermediate

**Concepts:** Conditionals, Loops, State Management, Input Validation, Game Design

---

## Description

Create an interactive text-based adventure game where the player navigates through different locations by typing commands. The game should have multiple paths, handle invalid input gracefully, and include at least one ending.

---

## Requirements

- Create at least 4-5 different locations/rooms
- Each location should have a description and options for where to go
- Allow the player to move between connected locations
- If the player enters an invalid option, ask them again (don't crash or skip)
- Include at least one ending (win, lose, or escape)
- Allow backtracking (going back to previous locations)

---

## Example

*Lines starting with `>` represent user input.*

```
You are in a creepy house! Would you like to go "upstairs" or into the "kitchen"?
> kitchen

There is a long countertop with dirty dishes everywhere. Off to one side
there is, as you'd expect, a refrigerator. You may open the "refrigerator"
or go "back".
> back

You are in a creepy house! Would you like to go "upstairs" or into the "kitchen"?
> upstairs

Upstairs you see a hallway. At the end of the hallway is the master
"bedroom". There is also a "bathroom" off the hallway. Or, you can
go back "downstairs". Where would you like to go?
> bedroom

...
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Use a variable to track the current location, and a loop that keeps running until the game ends.

</details>

<details>
<summary>Hint 2</summary>

Each location can be handled with if/else or switch/match statements based on the current location.

</details>

<details>
<summary>Hint 3</summary>

Wrap the input for each location in a loop that only exits when valid input is given.

</details>

---

## Bonus Challenges

- [ ] Add an inventory system (pick up and use items)
- [ ] Add random events or encounters
- [ ] Include multiple different endings based on choices
- [ ] Add a save/load feature using files
