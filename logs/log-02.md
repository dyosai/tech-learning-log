# Engineering Log 02 - JavaScript Fundamentals & Module 1 Mastery

<div align="center">

# ⚡ Engineering Log 02 — JavaScript Fundamentals & Module 1

[![Pathway](https://img.shields.io/badge/Pathway-Code_First_Girls-7A1CAC?style=flat-square)](https://codefirstgirls.org/)
[![Module Status](https://img.shields.io/badge/Status-Completed_Successfully-2ea44f?style=flat-square)]()
[![Quiz Scores](https://img.shields.io/badge/Quizzes-5%2F5_Clean_Sweep-blue?style=flat-square)]()

</div>

---

## 🎯 Module Overview & Technical Focus

- **Syntax & Rule Sets:** Mastered strict execution rules, case sensitivity, and statement terminators.
- **Variable Scope & State:** Implemented dynamic data containers using `let` and `const` to manage interactive numbers and strings.
- **Diagnostics & I/O:** Utilized the developer console for real-time script output and debugging.
- **DOM Integration & Element Targeting:** Programmatically targeted dynamic nodes using modern selectors (`document.getElementById`).
- **Event-Driven State Management:** Built interactive components (like the Stock Manager) combining event listeners with real-time UI state modifications.

---

## 💻 Implementation Highlight

```javascript
// Variable declaration and DOM node targeting from Module 1 exercise
const targetRole = "Software Engineer";
console.log("Target Role:", targetRole);
document.getElementById("role-val").textContent = targetRole;
```

---

## 📦 Stock Manager State Implementation

```javascript
// Exercise 6: Module 6 Event-Driven State Management & Dynamic Trigger
const stockParagraph = document.getElementById("stockParagraph");
const stockButton = document.getElementById("stockButton");
let stockCount = 10;

stockButton.addEventListener("click", () => {
  stockCount--;
  stockParagraph.textContent = `Stock: ${stockCount}`;
});

## 🐞 Error Prevention & Bug Ledger

| Bug / Error Encountered                      | Root Cause                                              | Permanent Solution                                          |
| :------------------------------------------- | :------------------------------------------------------ | :---------------------------------------------------------- |
| `TypeError: Assignment to constant variable` | Attempted runtime reassignment of a `const` declaration | Swapped declaration keyword to `let`                        |
| Unstyled Page / Blank Screen                 | Missing body structure or unlinked stylesheet path      | Restored base HTML elements and verified `<link>` reference |

## Engineering Takeaway:

Successfully bridged static HTML structures with dynamic JavaScript event listeners, cementing foundational fluency in modern frontend workflows.
```
