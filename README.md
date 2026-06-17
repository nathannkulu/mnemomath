# MathMnemo

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub repo size](https://img.shields.io/github/repo-size/nathannkulu/mnemomath)](https://github.com/nathannkulu/mnemomath)
[![GitHub last commit](https://img.shields.io/github/last-commit/nathannkulu/mnemomath)](https://github.com/nathannkulu/mnemomath)

**MathMnemo** is a fully interactive, zero-dependency web application for learning and practicing **multiplication tables**, **powers**, and **roots** — from 1×1 to 25×25, from n¹ to n²⁵, and from square roots up to the 25th root. Includes a **mnemonic quiz** and **16 mental math tricks**.

No installation required. Open a file in any browser and start learning.

---

## Features

### Multiplication
- Interactive tables from 1 × 1 to 25 × 25
- Choose a single number, a range, or display all tables at once
- Dynamic filtering and real-time updates

### Powers
- Compute n¹ through n²⁵ for any number
- Full reference table: n¹ to n¹⁰ for n = 1 to 25
- Powers of 2 (2ⁿ) from 1 to 25

### Roots
- Square roots, cube roots, and every root from the 2nd to the 25th
- Perfect root detection (highlighted in green)
- Root lists with configurable range

### Mnemonic Quiz
- Three subjects: multiplication, powers, roots  
- Configurable number range  
- Instant feedback with hints and scoring  
- Progress bar tracking

### Mental Math Tricks (16)
Practical shortcuts to replace traditional calculation methods:

| Trick | Method |
|---|---|
| ×11 | Split digits, insert sum |
| ×9, ×99, ×999 | Shift and subtract |
| ×25 | Divide by 4, ×100 |
| ×125 | Divide by 8, ×1000 |
| ×5 | Divide by 2, ×10 |
| ×50 | Divide by 2, ×100 |
| ×15 | ×10 + half of ×10 |
| ×12 | ×10 + ×2 |
| Reverse % | x% of y = y% of x |
| 15% tip | 10% + half of 10% |
| Squares ending in 5 | n(n+1) + 25 |
| Difference of squares | (a+b)(a−b) = a²−b² |
| Numbers near 100 | (100−a)(100−b) shortcut |
| Divisibility by 3/6/9 | Digit sum test |
| Rule of 72 | 72 ÷ rate = doubling time |
| Casting out nines | Verify any calculation |

---

## Files

| File | Description |
|---|---|
| `index.html` | Main app: quiz + mnemonic tricks + links to sections |
| `multiplication.html` | Dedicated multiplication section |
| `powers.html` | Dedicated powers section |
| `roots.html` | Dedicated roots section |
| `dynamic.html` | Combined dynamic view (all sections at once) |
| `full.html` | Complete static reference (printable) |
| `README.md` | This file |
| `LICENSE` | MIT License |

---

## Usage

1. Open any `.html` file in a web browser (Chrome, Edge, Firefox, Safari).
2. No server, no installation, no dependencies required — works directly from the file system.
3. Navigate between sections using the links at the top of each page.
4. Use the checkboxes and input fields to filter the displayed data.

### Print

The **Print** button (available in `dynamic.html` and `full.html`) renders the content in a printer-friendly format.

---

## Browser Support

All modern browsers (Chrome, Firefox, Edge, Safari, Opera). JavaScript must be enabled.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## Author

**Nathannkulu** — [GitHub](https://github.com/nathannkulu)
