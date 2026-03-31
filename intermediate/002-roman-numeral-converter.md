# Roman Numeral Converter

**Difficulty:** Intermediate

**Concepts:** String Parsing, Validation, Number Systems, Conditionals, Data Structures

---

## Description

Build a converter that can translate between Roman numerals and Arabic numbers (regular integers). The user chooses which direction to convert.

---

## Requirements

- Present a menu: Convert Roman to Number, or Number to Roman
- **Roman to Number:** Validate the input is a valid Roman numeral, then convert
- **Number to Roman:** Convert a positive integer to Roman numerals
- Handle invalid inputs gracefully

---

## Roman Numeral Reference

| Symbol | Value |
|--------|-------|
| I      | 1     |
| V      | 5     |
| X      | 10    |
| L      | 50    |
| C      | 100   |
| D      | 500   |
| M      | 1000  |

**Subtractive notation:** When a smaller value appears before a larger one, subtract it:
- IV = 4 (5 - 1)
- IX = 9 (10 - 1)
- XL = 40 (50 - 10)
- XC = 90 (100 - 10)
- CD = 400 (500 - 100)
- CM = 900 (1000 - 100)

---

## Example

**Roman to Number:**
```
Roman Numeral Converter
1. Roman to Number
2. Number to Roman
{User-Input} - 1
Enter a Roman numeral:
{User-Input} - LXVII
Result: 67
```

**Number to Roman:**
```
Roman Numeral Converter
1. Roman to Number
2. Number to Roman
{User-Input} - 2
Enter a number:
{User-Input} - 452
Result: CDLII
```

---

## Hints

<details>
<summary>Hint 1</summary>

Store the Roman numeral values in a data structure (dictionary/map/object) for easy lookup.

</details>

<details>
<summary>Hint 2</summary>

For Roman to Number: Compare each character with the next one to detect subtractive pairs.

</details>

<details>
<summary>Hint 3</summary>

For Number to Roman: Work from largest to smallest values. Include the subtractive pairs (CM, CD, XC, etc.) in your lookup table.

</details>

---

## Bonus Challenges

- [ ] Validate that Roman numerals follow proper rules (no more than 3 consecutive I, X, C, M)
- [ ] Support lowercase input for Roman numerals
- [ ] Handle numbers up to 3999 (standard Roman numeral limit)
- [ ] Add error messages for invalid Roman numerals like "IIII" or "VV"
