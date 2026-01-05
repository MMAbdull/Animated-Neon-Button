# 🔮 Animated Neon Button (Pure CSS)

A small UI experiment showcasing an animated neon-style button using **pure HTML & CSS**, with no JavaScript and no extra HTML elements.

This project focuses on **CSS pseudo-elements**, hover animations, and visual layering techniques.

---

## ✨ Features

- Neon glow effect
- Animated hover scaling
- CSS-only reflection effect
- No JavaScript
- No extra HTML markup
- Fully centered layout using Flexbox

---

## 🧠 What I Learned From This Project

This project helped me strengthen my understanding of:

- CSS pseudo-elements (`::before` and `::after`)
- Layering and stacking context (`position` + `z-index`)
- Hover animations and transitions
- Using transforms for visual depth
- Creating complex UI effects without extra HTML

---

## 🎯 Key CSS Techniques Used

### 1️⃣ `::after` — Animated Border Layer

The `::after` pseudo-element is used to create a glowing border **behind the button**:

- Covers the full button size
- Uses padding to simulate a border
- Positioned absolutely with `z-index: -1`
- Eliminates the need for extra wrapper elements

This keeps the HTML clean while adding visual complexity.

---

### 2️⃣ `::before` — Neon Reflection Effect

The `::before` pseudo-element simulates a neon light reflection:

- Positioned below the button
- Uses `perspective()` and `rotateX()` to fake depth
- `blur()` creates a soft glow
- Animated on hover for realism

This effect adds a subtle 3D illusion using only CSS.

---

### 3️⃣ Hover & Animation Effects

- `transform: scale()` for interactive feedback
- `box-shadow` intensifies on hover
- Smooth transitions for a polished feel

---

## 🛠 Technologies Used

- HTML5
- CSS3
- Flexbox
- CSS Transforms
- CSS Pseudo-elements

---

## 📸 Preview

_Add a GIF or screenshot here_

---

## 🚀 How to Run

Simply open `index.html` in your browser.

---

## 📌 Notes

This project is intentionally minimal to focus on **visual CSS techniques** rather than functionality.

---

## 👨‍💻 Author

Created by **Mohammad Abdullah**
