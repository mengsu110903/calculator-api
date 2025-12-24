
# 🧮 Modern Scientific Calculator

A sleek, modern **Scientific Calculator** built using **pure HTML, CSS, and JavaScript**.
This project features a clean dark-themed UI, responsive layout, scientific functions, and keyboard support — all without any external libraries or frameworks.

---

## 📌 Project Overview

The **Modern Scientific Calculator** is a single-page web application designed to perform both **basic arithmetic** and **scientific calculations** directly in the browser.

It uses:

* **HTML** for structure
* **CSS** for styling and theming
* **Vanilla JavaScript** for logic and interaction

No installation or build tools are required — just open the file in a browser.

---

## ✨ Features

### 🔢 Basic Calculator Functions

* Addition (`+`)
* Subtraction (`−`)
* Multiplication (`×`)
* Division (`÷`)
* Decimal support
* Clear All (`AC`)
* Backspace (`⌫`)

### 🧪 Scientific Functions

* Sine (`sin`)
* Cosine (`cos`)
* Tangent (`tan`)
* Logarithm base 10 (`log`)
* Natural logarithm (`ln`)
* Square root (`√`)
* Power / exponent (`xʸ`)
* Pi constant (`π`)

### ⌨️ Keyboard Support

You can use your keyboard for faster input:

* Numbers: `0–9`
* Operators: `+ - * / .`
* `Enter` → Calculate
* `Backspace` → Delete last character
* `C` → Clear all

### 🎨 UI & Design

* Modern **dark theme**
* Smooth hover and click animations
* Responsive layout
* Apple-inspired minimal design
* Clear expression and result display

---

## 🖥️ Technologies Used

| Technology       | Description                      |
| ---------------- | -------------------------------- |
| HTML5            | Application structure            |
| CSS3             | Styling, layout, animations      |
| JavaScript (ES6) | Calculator logic and interaction |

---

## 📂 Project Structure

```
modern-scientific-calculator/
│
├── index.html   # Main HTML file (includes CSS & JavaScript)
└── README.md    # Project documentation
```

> ⚠️ All CSS and JavaScript are embedded directly inside `index.html` for simplicity.

---

## 🚀 How to Run the Project

### Option 1: Open Locally

1. Download or clone this repository
2. Locate the `index.html` file
3. Double-click the file
   **OR**
4. Right-click → Open with → Any modern browser (Chrome, Edge, Firefox)

### Option 2: Use Live Server (Optional)

If using VS Code:

1. Install **Live Server** extension
2. Right-click `index.html`
3. Click **Open with Live Server**

---

## 🧠 How It Works

### Expression Handling

* User inputs are stored as a string (`expression`)
* Buttons and keyboard inputs append values to this string

### Calculation Logic

* JavaScript’s `Function()` constructor safely evaluates expressions
* Results are formatted using `toPrecision(12)` for accuracy
* Errors (invalid expressions) return `"Error"`

### Example:

```js
Function('"use strict"; return (' + expression + ')')();
```

---

## ⚠️ Limitations

* Trigonometric functions use **radians**, not degrees
* No calculation history
* No parentheses buttons (can be typed manually)
* Uses JavaScript evaluation (not recommended for untrusted input in production)

---

## 🔮 Possible Enhancements

* Degree / Radian toggle
* Parentheses buttons
* Calculation history panel
* Theme switch (light/dark)
* Mobile vibration feedback
* Modular JS file separation

## 📄 License

This project is **open for educational and personal use**.
You may modify and distribute it freely.

---

## 👨‍💻 Author

**Jeremy Eclarino**
Modern Scientific Calculator Project
