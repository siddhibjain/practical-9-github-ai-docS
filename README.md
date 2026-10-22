# 🧮 Python Calculator

A simple, user-friendly calculator built with Python that performs basic arithmetic operations. The project demonstrates fundamental Python programming concepts, including functions, conditional statements, user input, and error handling.

## 📌 Project Description

The **Python Calculator** is a beginner-friendly application designed to perform four basic mathematical operations: addition, subtraction, multiplication, and division.

It accepts numeric input from the user, processes the selected operation, and displays the calculated result. The program also handles division by zero to prevent runtime errors and provide a meaningful error message.

## ✨ Features

* ➕ **Addition:** Adds two numbers.
* ➖ **Subtraction:** Subtracts the second number from the first.
* ✖️ **Multiplication:** Multiplies two numbers.
* ➗ **Division:** Divides the first number by the second.
* ⚠️ **Division-by-Zero Handling:** Displays an error message when the user attempts to divide by zero.
* ⌨️ **User Input:** Accepts numbers and operations from the user.
* 📊 **Result Display:** Displays the result of the selected operation.
* 🪶 **Lightweight:** Requires no external Python libraries.

## 🛠️ Technologies Used

| Technology                | Purpose                                    |
| ------------------------- | ------------------------------------------ |
| Python 3                  | Core programming language                  |
| Functions                 | Organize calculation logic                 |
| Conditional Statements    | Select and execute operations              |
| Exception Handling        | Handle errors when implemented in the code |
| Terminal / Command Prompt | Run the calculator                         |

## 📂 Project Structure

```text
python-calculator/
│
├── calculator.py    # Main calculator program
├── README.md        # Project documentation
└── .gitignore       # Files excluded from version control (optional)
```

## 🚀 Installation

Follow these steps to set up and run the project on your computer.

### Prerequisites

* Python 3 installed on your computer.
* A code editor such as Visual Studio Code or Cursor.
* A terminal or command prompt.

### Step 1: Clone the Repository

If the project is hosted on GitHub, run:

```bash
git clone <your-repository-url>
```

Replace `<your-repository-url>` with your actual GitHub repository URL.

### Step 2: Navigate to the Project Directory

```bash
cd python-calculator
```

### Step 3: Verify Python Installation

Check whether Python is installed:

```bash
python --version
```

If that command does not work, try:

```bash
python3 --version
```

### Step 4: Run the Calculator

Execute the Python file using:

```bash
python calculator.py
```

On systems that use `python3`, run:

```bash
python3 calculator.py
```

**Note:** No additional packages are required for the basic calculator.

## 💻 Usage

1. Run the `calculator.py` file.
2. Enter the first number.
3. Enter the desired arithmetic operation.
4. Enter the second number.
5. View the result displayed in the terminal.

### Supported Operations

| Operation      | Symbol | Example | Result |
| -------------- | ------ | ------- | ------ |
| Addition       | `+`    | 10 + 5  | 15     |
| Subtraction    | `-`    | 10 - 5  | 5      |
| Multiplication | `*`    | 10 * 5  | 50     |
| Division       | `/`    | 10 / 5  | 2      |

### Example: Division by Zero

If the user enters `0` as the divisor, the calculator should display an appropriate error message instead of attempting the division.

## 📷 Sample Output

**Example 1: Addition**

```text
===== Python Calculator =====

Enter first number: 10
Enter operator (+, -, *, /): +
Enter second number: 5

Result: 15
```

**Example 2: Multiplication**

```text
===== Python Calculator =====

Enter first number: 6
Enter operator (+, -, *, /): *
Enter second number: 7

Result: 42
```

**Example 3: Division by Zero**

```text
===== Python Calculator =====

Enter first number: 10
Enter operator (+, -, *, /): /
Enter second number: 0

Error: Division by zero is not allowed.
```

*Note: The sample output illustrates the expected behavior. Your actual prompts and formatting may differ depending on your implementation.*

## 🧠 Concepts Learned

This project helps beginners practice the following programming concepts:

* Variables and data types
* Taking user input
* Arithmetic operators
* Functions and modular programming
* Conditional statements (`if`, `elif`, and `else`)
* Basic error handling
* Writing readable and maintainable code

## 🔮 Future Improvements

The calculator can be enhanced with additional functionality, including:

* [ ] Add support for exponentiation and modulo operations.
* [ ] Implement a continuous calculation loop.
* [ ] Add input validation for invalid numeric values.
* [ ] Create a graphical user interface (GUI) using Tkinter.
* [ ] Add calculation history.
* [ ] Support mathematical functions such as square root and percentage.
* [ ] Add automated unit tests using Python's `unittest` framework.
* [ ] Improve error messages and input handling.

## 🤝 Contributing

Contributions and suggestions are welcome!

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and test them.
4. Submit a pull request describing your improvements.

## 📄 License

This project is available for educational and personal use. If you plan to distribute it publicly, consider adding an appropriate open-source license, such as the MIT License.

## 👩‍💻 Author

**Siddhi Jain**

A beginner Python project created to practice programming fundamentals and build practical coding experience.

---

⭐ **If you find this project useful, consider giving the repository a star!**
