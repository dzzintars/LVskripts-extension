<p align="center">
  <img src="./icons/icon.png" alt="LVskripts logo" width="180">
</p>

<h1 align="center">LVskripts for Visual Studio Code</h1>

<p align="center">
  <strong>Snippets, syntax highlighting, and language support for <a href="https://github.com/superkaplis/LVskripts">LVskripts</a> — JavaScript with Latvian syntax.</strong>
</p>

<p align="center">
  
</p>

---

##  Features

-  **Syntax Highlighting** — Clean colorization for Latvian keywords, variables, loops, and functions in `.lv` files.
-  **Snippets & Autocompletion** — Write LVskripts faster with built-in code snippets and keyword suggestions.
-  **LVskripts Language Support** — Tailored editing experience for LVskripts inside Visual Studio Code.

---

##  Transpiler

To compile and run LVskripts code as JavaScript, install the **LVskripts** transpiler globally via npm:

```bash
npm install lvskripts -g
```

### Quick CLI Usage

| Command | Description |
| :--- | :--- |
| `lvskripts -run tests.lv` | Execute an LVskripts file directly |
| `lvskripts -compile tests.lv` | Transpile LVskripts code to JavaScript |
| `lvskripts -reverse tests.js` | Transpile JavaScript code to LVskripts |

> 🔗 **Transpiler GitHub Repository:** [github.com/superkaplis/LVskripts](https://github.com/superkaplis/LVskripts)

---

##  Example

```js
konstante cipari = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

priekš (mainīgais i no cipari) {
    ja (i % 2 === 1) {
        printēt(i);
    }
}
```