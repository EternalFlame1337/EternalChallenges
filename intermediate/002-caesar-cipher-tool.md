# Caesar Cipher Tool

**Difficulty:** Intermediate

**Concepts:** String Manipulation, File I/O, Encryption/Decryption, Modular Arithmetic, Menu Systems

---

## Description

Build a Caesar Cipher tool that can encrypt and decrypt messages. The Caesar Cipher shifts each letter in the message by a specified number of positions in the alphabet. Store the result in a file and allow users to view the last message.

---

## Requirements

- Present a menu with three options: Encrypt, Decrypt, or View Last Message
- **Encrypt:** Ask for a message and shift value, apply Caesar Cipher encryption, store in file
- **Decrypt:** Ask for a message and shift value, apply Caesar Cipher decryption, store in file
- **View:** Read and display the last message stored in the file
- Handle both uppercase and lowercase letters
- Non-alphabetic characters (spaces, numbers, punctuation) should remain unchanged

---

## How Caesar Cipher Works

Each letter is shifted by the specified amount:
- With shift 3: A becomes D, B becomes E, Z becomes C (wraps around)
- Decryption uses the reverse shift

---

## Example

**Encrypting:**
```
Welcome to the Caesar Cipher Tool. Would you like to encrypt, decrypt, or view?
{User-Input} - encrypt
What message would you like to encrypt?
{User-Input} - Hello World
What shift value would you like to use?
{User-Input} - 3
Your encrypted message is: Khoor Zruog
```

**Decrypting:**
```
Welcome to the Caesar Cipher Tool. Would you like to encrypt, decrypt, or view?
{User-Input} - decrypt
What message would you like to decrypt?
{User-Input} - Khoor Zruog
What shift value was used?
{User-Input} - 3
Your decrypted message is: Hello World
```

**Viewing:**
```
Welcome to the Caesar Cipher Tool. Would you like to encrypt, decrypt, or view?
{User-Input} - view
The last message was: Hello World
```

---

## Hints

<details>
<summary>Hint 1</summary>

Characters have numeric codes (ASCII/Unicode). You can convert between characters and numbers to perform the shift.

</details>

<details>
<summary>Hint 2</summary>

Use modulo (%) to handle wrapping around the alphabet. The alphabet has 26 letters.

</details>

<details>
<summary>Hint 3</summary>

Handle uppercase (A-Z) and lowercase (a-z) separately since they have different character codes.

</details>

---

## Bonus Challenges

- [ ] Add a "crack" option that tries all 26 shifts and displays results
- [ ] Support negative shift values
- [ ] Keep a history of all messages, not just the last one
- [ ] Use JSON format for storage instead of plain text
