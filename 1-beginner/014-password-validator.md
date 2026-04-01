# Password Validator

**Difficulty:** Beginner

**Concepts:** Strings, Conditionals, String Length, Validation

---

## Description

Create a program that checks if a password meets certain requirements.

This challenge teaches:
- Checking string properties (length)
- Combining multiple conditions
- Validating user input against rules

---

## Requirements

- Ask the user to create a password
- Check if the password meets these requirements:
  - At least 8 characters long
- Tell the user if their password is valid or not
- If invalid, explain why

---

## Example

*Lines starting with `>` represent user input.*

```
Create a password:
> hello
Password is too short! Must be at least 8 characters.
Your password is 5 characters.
```

```
Create a password:
> mysecretpassword
Password accepted!
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Most languages have a way to get the length of a string (e.g., `len()` in Python, `.length` in JavaScript/Java).

</details>

<details>
<summary>Hint 2</summary>

Compare the length to your minimum requirement using `>=` or `<`.

</details>

---

## Bonus Challenges

- [ ] Require at least one number in the password
- [ ] Require at least one uppercase letter
- [ ] Require at least one special character (!@#$%^&*)
- [ ] Check that the password doesn't contain the word "password"
- [ ] Show a password strength meter (weak/medium/strong)
