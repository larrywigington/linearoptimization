# PhD Optimization Learning: Linear Programming

Welcome to my GitHub repository dedicated to my PhD studies in optimization, with a focus on **Linear Programming**. This repository, maintained by [larrywigington](https://github.com/larrywigington), serves as a collection of notes, code implementations, and resources exploring core linear programming concepts, algorithms, and real-world applications.

---

## 📚 Reference Text

This work is deeply inspired by:

> **Bertsimas, D., & Tsitsiklis, J. N. (1997). _Introduction to Linear Optimization_. Athena Scientific.**

The repository supplements and expands on this text through a combination of theory, implementation, and experimentation.

---

## 🔍 Topics Covered

- Formulation of linear programming (LP) problems  
- The Simplex method and its algorithmic variants  
- Duality theory and complementary slackness  
- Sensitivity and post-optimality analysis  
- Interior-point methods (planned)  
- Applications in operations research, economics, and network flows  
- Python-based numerical implementation using **NumPy**, **SciPy**, and **Pyomo**

---

## 📁 Repository Structure

```text
phd-optimization-learning/
│
├── notes/         # Annotated textbook notes, derivations, and lecture-style writeups
├── code/          # Implementations of LP solvers and examples (Python + Jupyter)
├── problems/      # Problem sets with worked solutions and LaTeX exports
├── resources/     # Supplementary papers, articles, and helpful reference material
└── requirements.txt  # List of dependencies
```

---

## ⚙️ Getting Started

### Prerequisites

To use this repo:

- Python **3.10+** (or 3.13 if using newer syntax)
- Libraries:
  - `numpy`
  - `scipy`
  - `pyomo`
  - (optional) `jupyter`
- A solver compatible with Pyomo (GLPK, CBC, Gurobi, etc.)

> Install dependencies:
```bash
pip install -r requirements.txt
```

> To install GLPK on Mac via Homebrew:
```bash
brew install glpk
```

> For Windows users, see `code/INSTALL.md` for solver setup instructions.

---

### 🚀 Running Examples

To run a basic LP implementation:

```bash
python code/simplex_algorithm.py
```

Or launch the interactive notebook:

```bash
jupyter notebook code/linear_programming_examples.ipynb
```

---

## 📖 References

- Bertsimas, D., & Tsitsiklis, J. N. (1997). *Introduction to Linear Optimization*. Athena Scientific.
- Additional materials are listed in the `resources/` directory.

---

## 🤝 Contributing

This is a personal learning project, but suggestions and corrections are very welcome!  
Please open an issue or submit a pull request if you'd like to contribute.

---

## 📄 License

This repository is licensed under the MIT License. See `LICENSE` for full details.

---

Happy optimizing! 🚀
