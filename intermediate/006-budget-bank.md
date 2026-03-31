# Budget Bank

**Difficulty:** Intermediate

**Concepts:** File I/O, Loops, Conditionals, User Input, Data Persistence

---

## Description

Create a simple banking system that stores the user's balance in a file. Users can deposit money, withdraw money, or check their total balance. The balance persists between program runs.

---

## Requirements

- Store the balance in a file (e.g., "balance.txt")
- Present a menu with options: Withdraw, Store (Deposit), Check Total
- **Store:** Add the specified amount to the balance
- **Withdraw:** Remove the specified amount from the balance
- **Check Total:** Display the current balance
- The balance should persist after the program closes

---

## Example

*Lines starting with `>` represent user input.*

**Depositing:**
```
Welcome to Budget Bank. Would you like to withdraw, store, or check total?
> store
How much money would you like to store?
> 46
$46 has been stored.
```

**Withdrawing:**
```
Welcome to Budget Bank. Would you like to withdraw, store, or check total?
> withdraw
How much money would you like to withdraw?
> 11
$11 has been withdrawn.
```

**Checking balance:**
```
Welcome to Budget Bank. Would you like to withdraw, store, or check total?
> total
Your total is $35.
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Read the current balance from the file at the start, and write the new balance after each transaction.

</details>

<details>
<summary>Hint 2</summary>

Handle the case where the file doesn't exist yet (first run) by starting with a balance of 0.

</details>

<details>
<summary>Hint 3</summary>

Convert between string and number when reading/writing the file.

</details>

---

## Bonus Challenges

- [ ] Prevent withdrawing more than the current balance
- [ ] Add a transaction history log
- [ ] Support multiple accounts with different files
- [ ] Use JSON format instead of plain text
