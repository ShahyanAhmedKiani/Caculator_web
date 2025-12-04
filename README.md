# Caculator_web
# 🧮 Web-Based Scientific Calculator

A responsive, feature-rich scientific calculator built with **HTML, CSS, and JavaScript** for educational and practical use.



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


