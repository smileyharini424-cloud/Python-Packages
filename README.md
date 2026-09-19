# Python Packages

## Explanation

A Python package is a collection of related modules organized inside a directory. Packages help structure larger programs and make code easier to manage and reuse.

A package commonly contains an `__init__.py` file and one or more Python modules.

## Problem Statement

Create a Python package containing a module with arithmetic functions and import those functions into a main Python program.

## Features

* Creates a Python package
* Creates a reusable module
* Uses `__init__.py`
* Imports functions from a package
* Performs arithmetic operations

## How It Works

The project contains:

* `math_package/` – package directory
* `__init__.py` – identifies the package and can expose package-level functionality
* `math_operations.py` – contains arithmetic functions
* `main.py` – imports and uses functions from the package

## Technologies Used

* Python 3

## Program Flow

1. Create the package directory.
2. Create `__init__.py`.
3. Create the arithmetic module.
4. Define arithmetic functions.
5. Import the required functions into `main.py`.
6. Read two numbers.
7. Perform calculations.
8. Display the results.

## Sample Input

```text id="p8r2mv"
Enter first number: 15
Enter second number: 5
```

## Sample Output

```text id="x4k7qn"
Addition: 20
Subtraction: 10
Multiplication: 75
Division: 3.0
```

## Key Learning

* Understanding Python packages
* Creating package directories
* Using `__init__.py`
* Importing functions from packages
* Organizing reusable code

## File Location

```text id="n5c9wb"
Python-Packages/
├── main.py
└── math_package/
    ├── __init__.py
    └── math_operations.py
```

## Repository Structure

```text id="r3m6kp"
Python-Packages/
│
├── main.py
├── math_package/
│   ├── __init__.py
│   └── math_operations.py
└── README.md
```

## Author

V.Harini
