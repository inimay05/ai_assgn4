# ai_assgn4

# Constraint Satisfaction Problems (CSP) – Python Implementation

## 📌 Overview

This repository contains Python implementations of classical **Constraint Satisfaction Problems (CSP)**. Each problem is solved using **backtracking and constraint checking techniques**.

---

## 📚 Problems Implemented

### 1. Australia Map Coloring (`AusMap`)

The map coloring problem assigns colors to regions such that no two adjacent regions share the same color.

* Regions:
  WA, NT, Q, SA, NSW, V, T
* Constraint:
  Adjacent regions must have different colors
* Method:
  Backtracking

---

### 2. Telangana Map Coloring (`TelanganaMap`)

This program applies CSP to districts of Telangana using graph coloring.

* Representation:
  Districts are modeled as nodes and adjacency as edges

* Constraint:
  Adjacent districts must not have the same color

* Method:
  Backtracking

* Additional Feature:
  Graph visualization using Python libraries

---

### 3. Sudoku Solver (`SudokuSolver`)

The Sudoku puzzle is solved by filling a 9×9 grid while satisfying constraints.

* Constraints:

  * Each row must contain digits 1–9 without repetition
  * Each column must contain digits 1–9 without repetition
  * Each 3×3 subgrid must contain digits 1–9 without repetition

* Method:
  Backtracking with constraint validation

---

### 4. Cryptarithmetic Puzzle (`CryptarithmeticPuzzle`)

The following equation is solved:

SEND + MORE = MONEY

* Constraints:

  * Each letter is assigned a unique digit
  * Leading digits cannot be zero
* Method:
  Backtracking with constraint checking

---

## ⚙️ Requirements

* Python 3.8 or higher

---

## 📦 Dependencies

Install the required libraries using:

```bash
pip install networkx matplotlib
```

* `networkx` is used for graph representation
* `matplotlib` is used for visualization

---

## ▶️ Execution

Run each program using:

```bash
python AusMap.py
python TelanganaMap.py
python SudokuSolver.py
python CryptarithmeticPuzzle.py
```

---

## 📊 Output

Each program prints the solution in the console.

Example:

```
Hyderabad = Red
Medchal = Green
Rangareddy = Blue
```

All outputs satisfy the constraints defined for each problem.

---
