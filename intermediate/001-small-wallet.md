# Small Wallet

**Difficulty:** Intermediate

**Concepts:** Variables, Loops, Conditionals, User Input, Basic Math

---

## Description

Create a simple shopping simulator. The user starts with a set amount of money and can purchase items from a menu. The program tracks their remaining balance and prevents purchases they can't afford.

---

## Requirements

- Start the user with $30
- Display a menu of items with prices:
  - Can of Baked Beans - $10
  - Meaty Cow Leg - $25
  - Juice - $7
  - Sugar - $5
- After each purchase, show the remaining balance
- If the user can't afford an item, display a message and don't deduct money
- Keep asking until the user can't afford anything or chooses to quit

---

## Example

```
What would you like to purchase? You have $30
{User-Input} - Meaty Cow Leg
You have purchased Meaty Cow Leg.

What would you like to purchase? You have $5
{User-Input} - Juice
You cannot afford Juice.

What would you like to purchase? You have $5
{User-Input} - Sugar
You have purchased Sugar.

You're out of money! Thanks for shopping.
```

---

## Hints

<details>
<summary>Hint 1</summary>

Use a loop that continues while the user has money remaining.

</details>

<details>
<summary>Hint 2</summary>

Before processing a purchase, check if the user's balance is greater than or equal to the item's price.

</details>

<details>
<summary>Hint 3</summary>

Consider storing items and prices together (like in a dictionary/map/object) for cleaner code.

</details>

---

## Bonus Challenges

- [ ] Add a "quit" option so users can leave early
- [ ] Display the menu with prices each time
- [ ] Show a receipt at the end listing all purchased items
- [ ] Add item quantities (e.g., buy 2 cans of beans)
