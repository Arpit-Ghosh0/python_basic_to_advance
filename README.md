# 🐍 Python: From Basics to Advanced

A complete, hands-on Python learning path — from your first `print("Hello, World!")` to NumPy, Pandas, Matplotlib, and real mini-projects. Every notebook is heavily commented and explained in plain English, meant to be read *and* run.

## 📂 Repository Structure

```
.
├── 01_basics/              # Variables, data types, operators, strings, I/O
├── 02_control_flow/        # if/elif/else, loops, break/continue/pass, match-case
├── 03_functions/           # args/kwargs, defaults, lambda, recursion, scope
├── 04_data_structures/     # Lists, tuples, sets, dicts, comprehensions
├── 05_modules_packages/    # Imports, the standard library, building your own packages
├── 06_file_handling/       # Reading/writing text, JSON, and CSV files
├── 07_oop/                 # Classes, inheritance, magic methods, properties, ABCs
├── 08_exceptions/          # try/except/else/finally, custom exceptions
├── 09_python_advanced/     # Generators, decorators, context managers, closures, type hints
├── 10_numpy/                # Arrays, broadcasting, linear algebra, performance
├── 11_pandas/               # DataFrames, cleaning data, groupby, merging, time series
├── 12_matplotlib/           # Chart types, styling, subplots, the OOP plotting API
├── 13_projects/             # Mini-projects combining everything above
├── .gitignore
└── README.md
```

## 🎯 What's Covered

**Core Python (`01_basics` → `09_python_advanced`)**
Comments & variables, data types & casting, operators, strings, control flow, functions, data structures & comprehensions, modules & packages, file handling, OOP (inheritance, encapsulation, magic methods, ABCs), exception handling, and advanced topics — generators, decorators, context managers, closures, functional tools (`map`/`filter`/`reduce`), type hints, the walrus operator, and a concurrency overview (threading/asyncio).

**Data Stack (`10_numpy` → `12_matplotlib`)**
NumPy arrays and vectorized math, Pandas DataFrames for real tabular data work, and Matplotlib for turning that data into charts.

**Projects (`13_projects`)**
Small, complete applications that tie concepts together: a to-do list manager, a word frequency counter, a calculator, a CSV-backed contact book, a combined NumPy + Pandas + Matplotlib data analysis pipeline, and a password strength checker.

## 🚀 Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```

2. **Set up an environment**
   ```bash
   python -m venv venv
   source venv/bin/activate      # Windows: venv\Scripts\activate
   pip install jupyter numpy pandas matplotlib
   ```

3. **Launch Jupyter**
   ```bash
   jupyter notebook
   ```

4. Open any notebook and run the cells in order (`Shift + Enter`) — later cells sometimes build on earlier ones.

## 📖 How to Use This Repo

- **New to Python?** Start at `01_basics` and work straight through to `09_python_advanced`.
- **Know the basics, want the data stack?** Jump to `10_numpy`, then `11_pandas`, then `12_matplotlib`.
- **Want to see it all in action?** `13_projects` has complete, runnable mini-apps.
- Each notebook is self-contained with markdown explanations above every code cell, so you can also use it as a quick reference — search for the concept you need instead of reading top to bottom.

## 🤝 Contributing

Found a bug, a typo, or want to add a topic that's missing? PRs and issues are welcome.

## 📄 License

Feel free to use this for your own learning. Consider adding a license (e.g. MIT) if you want to make reuse terms explicit.

---

⭐ If this helped you, consider starring the repo!
