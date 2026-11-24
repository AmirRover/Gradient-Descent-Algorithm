# Gradient Descent Algorithm

An interactive implementation of the **Gradient Descent Optimization Algorithm** using Python and Jupyter Notebook.

This project demonstrates the fundamentals of Gradient Descent through different mathematical functions, manual algorithm implementation, user-defined equations, and animated visualizations of the optimization process.

The project focuses on understanding how Gradient Descent works mathematically and computationally, how learning rates affect convergence, and how the algorithm approaches minimum points through iterative updates.

---

## Project Overview

Gradient Descent is an iterative optimization algorithm widely used in Machine Learning, Deep Learning, and Numerical Optimization.

The algorithm minimizes a function by repeatedly updating its parameters in the direction opposite to the gradient.

This project explores three different implementations:

- Manual Gradient Descent using a quadratic function.
- Manual Gradient Descent using a quartic function.
- Interactive Gradient Descent with user-defined mathematical expressions.

It also includes animated demonstrations to visualize the optimization process.

## Features

- **Manual Implementation:** Implementing Gradient Descent from scratch.
- **Quadratic Function:** Optimization of a second-degree polynomial.
- **Quartic Function:** Optimization of a fourth-degree polynomial.
- **User Input:** Accepting custom mathematical expressions.
- **Symbolic Differentiation:** Automatically calculating derivatives using SymPy.
- **Numerical Computation:** Performing mathematical operations using NumPy.
- **Data Processing:** Utilizing Pandas for data handling.
- **Interactive Visualization:** Displaying mathematical functions and optimization paths.
- **Algorithm Animation:** Visualizing parameter updates through animated plots and HTML display.

---

## Project Structure

```text
Gradient-Descent-Algorithm/
│
├── Animations of Algorithm/
│   ├── Gradient Descent (Manual).mp4
│   └── Gradient Descent (Manual) fx^4.mp4
│
├── data/
│
├── models/
│
├── Gradient Descent (Manual).ipynb
├── Gradient Descent (Manual) fx^4.ipynb
├── Gradient Descent (User Input).ipynb
│
├── README.md
└── .gitignore
```

## Notebooks

### 1. Gradient Descent (Manual)

Implementation of Gradient Descent from scratch using a quadratic function:

\[
f(x) = x^2
\]

This notebook explores:

- Manual implementation of the optimization algorithm.
- Gradient calculation.
- Learning rate configuration.
- Iterative parameter updates.
- Visualization of the optimization process.

### 2. Gradient Descent (Manual) – Quartic Function

Applying Gradient Descent to a fourth-degree polynomial:

\[
f(x) = x^4
\]

This notebook demonstrates how the algorithm behaves with a different mathematical function and explores its convergence behavior.

### 3. Gradient Descent (User Input)

An interactive implementation that allows users to enter their own mathematical expressions.

Key capabilities:

- Receiving mathematical functions from users.
- Parsing mathematical expressions.
- Calculating symbolic derivatives using SymPy.
- Converting symbolic expressions into numerical functions.
- Applying Gradient Descent to user-defined functions.
- Visualizing the optimization process.
- Displaying animated optimization results.

---

## Animations & Demonstrations

This project includes two MP4 video demonstrations showing the Gradient Descent optimization process.

### 1. Quadratic Function – \(f(x)=x^2\)

Demonstrates the iterative optimization process and how the algorithm approaches the minimum point of a quadratic function.

[▶ Watch Gradient Descent (Manual) – MP4](<Animations of Algorithm/Gradient Descent (Manual).mp4>)

### 2. Quartic Function – \(f(x)=x^4\)

Visualizes the optimization process for a quartic function and demonstrates how gradient-based updates move toward its minimum.

[▶ Watch Gradient Descent (Manual) fx^4 – MP4](<Animations of Algorithm/Gradient Descent (Manual) fx^4.mp4>)

---

## Mathematical Foundation

Gradient Descent updates the parameter iteratively using the following equation:

\[
x_{n+1}=x_n-\eta f'(x_n)
\]

Where:

- \(x_n\): Current parameter value.
- \(\eta\): Learning rate (step size).
- \(f'(x_n)\): Derivative of the function at the current point.
- \(x_{n+1}\): Updated parameter value.

The optimization process continues until a stopping condition is reached, such as a maximum number of iterations or a sufficiently small gradient.

---

## Technologies & Libraries

| Technology / Library | Alias | Purpose |
|---|---|---|
| Python 3.12 | — | Core programming language |
| Jupyter Notebook | — | Interactive development |
| NumPy | `np` | Numerical computations |
| SymPy | `sp` | Symbolic mathematics and differentiation |
| Pandas | `pd` | Data processing and manipulation |
| Matplotlib | `plt` | Plotting and visualization |
| IPython Display | `HTML` | Rendering HTML content in notebooks |

## Installation & Setup

### Prerequisites

- Python 3.12
- Jupyter Notebook
- pip package manager

### 1. Clone the Repository

```bash
git clone https://github.com/AmirRover/Gradient-Descent-Algorithm.git
```

### 2. Navigate to the Project Directory

```bash
cd Gradient-Descent-Algorithm
```

### 3. Create a Virtual Environment (Optional)

```bash
python3 -m venv .venv
```

Activate the environment on macOS / Linux:

```bash
source .venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install numpy sympy pandas matplotlib jupyter ipython
```

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open any of the three notebooks and execute the cells to explore the implementations.

---

## Learning Objectives

This project provides practical experience with:

- Understanding Gradient Descent and numerical optimization.
- Implementing optimization algorithms from scratch.
- Working with derivatives and symbolic mathematics.
- Understanding the role of learning rates.
- Exploring convergence behavior across different functions.
- Processing mathematical expressions dynamically.
- Visualizing optimization algorithms using Matplotlib.
- Creating animated visualizations in Jupyter Notebook.

---

## Author

**Amirreza Barati**

GitHub: [@AmirRover](https://github.com/AmirRover)

Project Repository: [Gradient Descent Algorithm](https://github.com/AmirRover/Gradient-Descent-Algorithm)

---

*Developed for educational purposes to explore the mathematical foundations and practical implementation of Gradient Descent optimization.*