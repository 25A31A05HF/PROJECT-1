                                              ** 🧮 Simple Calculator in C**

## 📌 Project Description

A simple command-line calculator written in C that performs basic arithmetic operations such as addition, subtraction, multiplication, and division using user input.

---

## ⚙️ Features

* Supports +, -, *, /
* Uses `switch-case` for operation handling
* Handles division by zero
* Displays results with precision (2 decimal places)

---

## 🧠 Logic Used

* Takes operator as input (`char`)
* Takes two numbers (`double`)
* Uses `switch` to perform the selected operation
* Includes error handling for invalid operator and division by zero

---

## ▶️ How to Run

### Compile

```bash id="l3n7yy"
gcc calculator.c -o calculator
```

### Execute

```bash id="p9k3rx"
./calculator
```

---

## 💻 Sample Output

```id="c5o1b2"
Enter an operator (+, -, *, /): *
Enter two operands: 6 4
6.00 * 4.00 = 24.00
```

---

## ⚠️ Error Handling

* Displays error for invalid operator
* Prevents division by zero

---

## 📂 File Structure

```id="h3x2nm"
calculator.c
README.md
```

---

## 🚀 Future Improvements

* Add loop for continuous calculations
* Menu-driven interface
* Support more operations (modulus, power)

---

## 📜 License

MIT License
