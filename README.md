# Scheme Interpreter in TypeScript

This is a Scheme interpreter implemented from scratch using TypeScript. It was developed as a personal project to deepen my understanding of interpreters, recursion, lexical scoping, and functional language principles.

## 🎯 Project Objective

To build a working interpreter that can evaluate a subset of the Scheme programming language. The goal was to support key features such as S-expressions, lambda expressions, recursion, and variable scoping.

## ⚙️ Key Features

- Parsing and evaluation of S-expressions
- Support for first-class functions and closures
- Lexical scoping with environments
- `define`, `lambda`, `if`, `begin`, and `quote` expressions
- Built-in arithmetic and list operations
- REPL interface for interactive evaluation

## 🛠 Technologies Used

- TypeScript
- Node.js
- Inquirer (for optional CLI interactions)
- Jest (for unit testing)

## 🚀 How to Run

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run the interpreter:
   ```bash
   npm start
   ```

3. Or launch the REPL:
   ```bash
   npm run repl
   ```

4. Run tests:
   ```bash
   npm test
   ```

## 🧪 Sample Code

```scheme
(define square (lambda (x) (* x x)))
(square 5) ;; => 25

(define factorial
  (lambda (n)
    (if (= n 0)
        1
        (* n (factorial (- n 1))))))
(factorial 5) ;; => 120
```

## ✍️ Author

- [Niv Yaakobov](https://github.com/Niv-Yaakobov)

> Developed as a personal learning project to explore language implementation and interpreter design using TypeScript.
