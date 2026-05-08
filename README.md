# Assignment 2 — EDS 232

**Regualrization, PCA and Decision Trees**

This repository contains the starter notebooks and files for Assignment 3. You will work across three tasks that focus on regularization, PCA, decision trees, and working with high dimensional data. 

---

## Repository Structure

```
assignment-3/
├── task1/
│   ├── hw3-task1.ipynb
│   └── tests/            # Autograder tests for Task 1
│       ├── q1.py
│       ├── q2.py
│       └── ...
├── task2/
│   ├── hw3-task2.ipynb
│   └── tests/            # Autograder tests for Task 2
│       ├── q1.py
│       ├── q2.py
│       └── ...
├── .gitignore
└── README.md
```

---



## Getting Started

### 1. Fork this repository

Click **Fork** at the top right of this page to create your own copy under your GitHub account.

### 2. Clone your fork

Open a terminal and run:

```bash
git clone https://github.com/YOUR-USERNAME/assignment-3.git
cd assignment-2
```

### 3. Open the notebooks

Launch JupyterLab or your preferred environment from inside the `assignment-3` directory. Do not move notebook files out of the repository folder.

### 4. Work through the tasks

Open each file and follow the instructions. For the `.ipynb` notebooks, always **run the first cell first** to initialize the Otter autograder before attempting any exercises.

### 5. Commit and push regularly

```bash
git add .
git commit -m "describe what you completed"
git push
```

---

## Autograder (Otter Grader)

Tasks 1 and 2 use `otter-grader` for automatic feedback.

- Run the **first cell** of each notebook to initialize the grader before anything else.
- After each exercise, run the `grader.check("qN")` cell to check your answer immediately.
- Before submitting, run the final `grader.check_all()` cell and leave its output visible — Gradescope uses this output as part of your grade.
- Do **not** modify or delete any locked `grader.check()` cells.

---

## Submitting to Gradescope

1. Make a final commit and push to ensure all your work is on GitHub.
2. Go to Gradescope and open the Assignment 3 portal.
3. Select **GitHub** as your submission method.
4. Choose your forked repository and the `main` branch.

Gradescope pulls directly from your repository at the time of submission. Make sure all notebooks have been run top-to-bottom and all outputs are visible before your final push.

---
