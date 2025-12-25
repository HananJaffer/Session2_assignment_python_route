# Python Control Flow & Error Handling 🐍

![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)
![Topic](https://img.shields.io/badge/topic-Control--Flow-orange)
![Topic](https://img.shields.io/badge/topic-Error--Handling-red)

## 📋 Overview
This repository contains the completion of the **Session 2 Assignment** focused on Python's decision-making and iteration capabilities. The script processes numerical data and exam scores using robust logic to handle unexpected user behavior.

## 🚀 Features
The assignment is broken down into four key modules:

### 🔹 A — Basic: Number Classifier
- Identifies if a number is **Positive, Negative, or Zero**.
- Determines if the number is **Even or Odd**.

### 🔹 B — Intermediate: Input Processor
- Accepts 5 sequential inputs.
- Calculates running **Sum**, **Positive Count**, and **Negative Count**.
- Uses `break` to exit if `0` is entered and `continue` to skip invalid non-numeric text.

### 🔹 C — Advanced: Score Analyzer
- Processes a list of exam scores: `[85, 92, 78, 65, 48, 90]`.
- Classifies scores into categories: 
  - **Excellent** (≥90), **Good** (≥75), **Average** (≥60), and **Poor** (<60).
- Generates a final distribution summary.

### 🌟 Bonus: Robust Mini-Analysis
- Handles bulk input (comma-separated).
- Implements `try/except` blocks to catch **Empty Inputs** and **ValueError** exceptions.

---

## 🛠️ Technical Concepts Used
| Concept | Implementation |
| :--- | :--- |
| **Branching** | `if`, `elif`, `else` |
| **Loops** | `for` (fixed range/lists), `while` (input validation) |
| **Flow Control** | `break` (early exit), `continue` (error skipping) |
| **Error Handling** | `try...except` for data integrity |
| **Data Types** | Lists, Dictionaries, Floats, and Strings |

---

## 💻 Getting Started

### Prerequisites
- Python 3.6 or higher installed.

### Installation & Execution
1. Clone this repository:
  ```bash
    git clone https://github.com/HananJaffer/Session2_assignment_python_route.git
  ```

2. Navigate to the project directory:
  ```bash
  cd python-control-flow
  ```


3. Run the script:
  ```bash
    python session2_assignment.py
  ```
