# JavaScript Assignment

This repository contains solutions to basic JavaScript exercises. The exercises are designed to practice expressions, arithmetic operations, comparisons, and JavaScript functions.

---

## **Q1: Evaluate each of the following JavaScript expressions and show the value**

| #   | Expression                      | Result            |
|-----|----------------------------------|-------------------|
| 1   | `-5 * 3`                        | `-15`             |
| 2   | `"JavaScript " + 50`            | `"JavaScript 50"` |
| 3   | `17 % 5`                        | `2`               |
| 4   | `5 % 17`                        | `5`               |
| 5   | `5 / 10`                        | `0.5`             |
| 6   | `(4 === '4')`                   | `false`           |
| 7   | `(4 != 5)`                      | `true`            |
| 8   | `(7 <= 8)`                      | `true`            |
| 9   | `"Hello" + 5`                   | `"Hello5"`        |
| 10  | `Math.ceil(x) - Math.floor(x)`  | `0` (if `x` is an integer) |
| 11  | `Math.pow(x, 2)`                | Depends on the value of `x` |

---

## **Q2: Read a number and display it using alert**

### Description
A simple script that reads a number from the user using `prompt` and displays it using `alert`.

**Code:**
```javascript
let number = prompt("Enter a number:");
alert("You entered: " + number);
