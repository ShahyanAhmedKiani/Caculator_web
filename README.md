# Caculator_web
# 🧮 Web-Based Scientific Calculator

A responsive, feature-rich scientific calculator built with **HTML, CSS, and JavaScript** for educational and practical use.

![Scientific Calculator Preview](preview.png) *(Optional: add screenshot)*

## ✨ Features

### 🔢 Basic Operations
- Addition (`+`)
- Subtraction (`−`)
- Multiplication (`×`)
- Division (`÷`)
- Decimal number support

### 📐 Scientific Functions
- Trigonometric: `sin`, `cos`, `tan` *(input in radians)*
- Logarithmic: `log` (base 10)
- Exponential: `exp` (eˣ)
- Power: `x^y`
- Square root: `√x`
- Mathematical constant: `π` (pi)
- Parentheses for expression grouping: `( )`

### 🎮 Special Buttons
| Button | Function |
|--------|---------|
| **C** | Clear entire display |
| **⌫** | Delete last character |
| **=** | Evaluate and display result |
| **π** | Insert `Math.PI` (≈3.14159) |

### 📱 Design & Responsiveness
- Clean, modern UI with color-coded buttons
- Grid-based layout using CSS Grid
- Fully responsive (works on mobile, tablet, and desktop)
- Real-time expression preview

## 🚀 How to Use

1. **Clone or download** this project.
2. Open `index.html` in any modern web browser.
3. Use the on-screen buttons to build expressions.
4. Press **`=`** to compute the result.
5. Use **`C`** to reset or **`⌫`** to correct mistakes.

> 💡 **Note**: Trigonometric functions use **radians** (e.g., `sin(1)` = sine of 1 radian).

### Example Inputs:
- `sin(π/2)` → `1`
- `√(16)` → `4`
- `2^3` → `8`
- `log(100)` → `2`
- `exp(0)` → `1`

## 🛠️ Technical Implementation

- **HTML**: Semantic structure with button-driven input
- **CSS**: Responsive grid layout, hover effects, and mobile-first design
- **JavaScript**:
  - `insert()` – Appends values to the display
  - `clearDisplay()` – Resets calculator
  - `deleteLast()` – Removes last character
  - `calculate()` – Safely evaluates expressions with:
    - Symbol replacement (`sin` → `Math.sin`)
    - Automatic parenthesis balancing
    - Error handling for invalid syntax

> 🔒 **Security Note**: Uses `Function()` constructor instead of `eval()` for safer expression evaluation (acceptable in button-only input context).

## 📁 Project Structure
