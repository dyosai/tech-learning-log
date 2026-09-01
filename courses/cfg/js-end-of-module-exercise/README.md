<div align="center">

# 📦 JavaScript End-of-Module Exercise

[![Pathway](https://img.shields.io/badge/Pathway-Code_First_Girls-7A1CAC?style=flat-square)](https://codefirstgirls.org/)
[![Focus](https://img.shields.io/badge/Focus-State_Management_%26_DOM-blue?style=flat-square)]()
[![Status](https://img.shields.io/badge/Status-Completed-2ea44f?style=flat-square)]()

_Hands-on practical application showcasing event listeners, DOM node manipulation, and state-driven UI updates._

</div>

---

## ⚡ Technical Architecture & Implementation

- **DOM Node Targeting:** Programmatically accessed specific HTML elements utilizing modern selection methods (`document.getElementById`).
- **Event-Driven Execution:** Bound interactive user actions directly to JavaScript execution layers (`addEventListener`).
- **State Tracking & Mutation:** Managed mutable data states (`let stockCount`) to dynamically modify text nodes and attributes in real time.

---

## 💻 Core Implementation Code

```javascript
// Interactive Stock Manager State Handler
const stockParagraph = document.getElementById("stockParagraph");
const stockButton = document.getElementById("stockButton");
let stockCount = 10;

stockButton.addEventListener("click", () => {
  stockCount--;
  stockParagraph.textContent = `Stock: ${stockCount}`;
});
```
