                                                    ** 🧮 Simple Calculator in C**

## 📌 Project Description

A command-line calculator written in C that performs basic arithmetic operations including addition, subtraction, multiplication, division, and modulus using user input.

---

## ⚙️ Features

* Addition (+)
* Subtraction (-)
* Multiplication (*)
* Division (/)
* Modulus (%) using `fmod()`
* Handles division by zero
* Displays output with 2 decimal precision

---

## 🧠 Logic Used

* Takes operator as input (`char`)
* Takes two numbers (`double`)
* Uses `switch-case` for operation selection
* Uses `fmod()` for modulus operation
* Handles invalid operator and division errors

---

## ⏱️ Time Complexity

**O(1)**
Executes a fixed number of operations regardless of input.

---

## 💾 Space Complexity

**O(1)**
Uses constant memory (few variables only).

---

## ▶️ How to Run

Compile:

```bash id="c1x9nq"
gcc calculator.c -o calculator -lm
```

Run:

```bash id="o7k3vr"
./calculator
```

---

## 💻 Sample Input & Output

### Addition

```id="m9q2sw"
Enter an operator (+, -, *, /, %): +
Enter two operands: 4 3
4.00 + 3.00 = 7.00
```

### Modulus

```id="6v4kxp"
Enter an operator (+, -, *, /, %): %
Enter two operands: 10 3
10.00 % 3.00 = 1.00
```

### Division by Zero

```id="8l1rty"
Enter an operator (+, -, *, /, %): /
Enter two operands: 5 0
Error! Division by zero is not allowed.
```

### Invalid Operator

```id="z3w8bn"
Enter an operator (+, -, *, /, %): @
Enter two operands: 2 2
Error! Operator is not correct.
```

---

## 🚀 Future Improvements

* Add loop for continuous calculations
* Menu-driven interface
* Add advanced operations

---

## 📜 License

MIT License
