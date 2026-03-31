# Temperature Converter

**Difficulty:** Beginner

**Concepts:** Variables, Math, User Input, Formulas

---

## Description

Create a program that converts temperatures between Celsius and Fahrenheit.

This challenge teaches:
- Applying mathematical formulas in code
- Getting input and producing calculated output
- Working with decimal numbers

---

## The Formulas

**Celsius to Fahrenheit:** `F = (C × 9/5) + 32`
**Fahrenheit to Celsius:** `C = (F - 32) × 5/9`

---

## Requirements

- Ask the user which conversion they want (C to F, or F to C)
- Ask for the temperature value
- Calculate and display the converted temperature

---

## Example

*Lines starting with `>` represent user input.*

```
Convert (C)elsius to Fahrenheit or (F)ahrenheit to Celsius?
> C
Enter temperature in Celsius:
> 100
100°C is 212°F
```

```
Convert (C)elsius to Fahrenheit or (F)ahrenheit to Celsius?
> F
Enter temperature in Fahrenheit:
> 32
32°F is 0°C
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Be careful with integer vs decimal division. In some languages, `9/5` equals `1` (integer division), not `1.8`. You may need to write `9.0/5.0` or use explicit conversion.

</details>

<details>
<summary>Hint 2</summary>

Follow the order of operations: multiplication and division before addition and subtraction. Use parentheses to be safe.

</details>

---

## Bonus Challenges

- [ ] Round the result to 1 or 2 decimal places
- [ ] Add Kelvin conversion (K = C + 273.15)
- [ ] Let the user convert multiple temperatures in a loop
- [ ] Display both conversions at once (show C→F and F→C)
