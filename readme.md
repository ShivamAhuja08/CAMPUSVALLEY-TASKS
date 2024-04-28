# Calculator Application

This is a simple calculator application built using Python's Tkinter library. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

## How It Works

The calculator application consists of a graphical user interface (GUI) with buttons for numbers, arithmetic operators, and a text entry field to display the input and result. Users can input numbers and perform calculations by clicking on the buttons. 

### Features:
- Addition (`+`)
- Subtraction (`-`)
- Multiplication (`*`)
- Division (`/`)
- Percentage (`%`) [For getting a remainder]
- Clear (`C`)
- Equals (`=`)

When the user clicks the "=" button, the application evaluates the expression entered in the text entry field using Python's `eval()` function. If the expression is valid, it computes the result and displays it in the text entry field. If the user enters an invalid or incorrect input like: '+' or any other operator at a same time, it will generate an **ERROR**

## How to Run

1. Clone or download the project repository to your local machine.
2. Navigate to the project directory in the terminal.
3. Run the following command to execute the calculator application:

   ```bash
   python calculator.py
   ```

# Password Generator

This is a simple password generation application built using Python's Tkinter library. It allows users to generate random passwords based on their input for name and desired password length.

## How It Works

The password generation application consists of a graphical user interface (GUI) with entry fields for the user's name and desired password length. Upon clicking the "Create Strong password" button, the application generates a random password of the specified length and displays it in the designated entry field.

### Features:
- Enter your name
- Specify password length
- Create Strong password
- Copy password to clipboard

When the user clicks the "Create Strong password" button, the application generates a random password by selecting random characters from ASCII range 33 to 126 (which includes printable characters, symbols, and punctuation). The generated password is then displayed in the entry field.

## How to Run

1. Clone or download the project repository to your local machine.

2. Navigate to the project directory in the terminal.

3. Run the following command to execute the password generation application:

   ```bash
   python pwdGenerator.py
   ```

