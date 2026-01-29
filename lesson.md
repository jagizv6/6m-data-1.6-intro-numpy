# Lesson 1.6 – NumPy for Beginners (Agenda)

Total Duration: 3 hours  
Environment: Google Colab or VS Code Jupyter

---

## Welcome & Outcomes

- Introduce the session and goals:
  - Understand what NumPy is and why it matters
  - Create and inspect basic arrays
  - See how NumPy compares to Python lists on performance

---

## Part 1: Performance Benchmark

Notebook: **“Part 1: Performance Benchmark”** section and code cell.[file:1]

- Walk through:
  - `import numpy as np`
  - Creating a 1,000,000‑element NumPy array and Python list
  - `%timeit` comparison: NumPy vectorized multiply vs list comprehension
- Quick learner activity:
  - Learners run the timing cell and briefly describe what they observe

---

## Part 2: The ndarray

Notebook: **“Part 2: The ndarray (N-dimensional array)”** and the demo cell creating `arr1` and `arr2`.[file:1]

- Concept:
  - `ndarray` as a container for homogeneous numeric data
  - Key attributes: `.shape`, `.dtype`, `.ndim`
- Demo:
  - Create 1D and 2D arrays from Python lists
  - Print the array, its shape, dtype, and number of dimensions
- Short practice:
  - Learners create their own small 1D and 2D arrays and inspect attributes

---

## Data Types and Casting

Notebook: **“Data Types and Casting”** markdown and casting demo cell.[file:1]

- Concept:
  - NumPy dtypes (`float64`, `int32`, etc.)
  - Casting with `.astype()`
  - Truncation when casting float → int
- Demo:
  - Create a float array, cast to `int32`, and inspect before/after
  - Convert string numbers to float using `.astype(float)`
- Exercise (in-notebook):
  - **[EXERCISE 1: Creation & Casting]**
    - 3×4 ones array → cast to `float32`
    - String array `['1.25', '-9.6', '42']` → cast to `float`
  - Learners implement solutions in the “Your code here” cell

---

## Guided Practice 1

Notebook: Re-use and extend the existing **Exercise 1** cell.

- Instructor adds a couple of extra prompts live:
  - Check `shape` and `dtype` of each created array
  - Create a new array and try casting to different integer types
- Learners work individually or in pairs
- Quick share-out of 1–2 solutions

---

## Part 3: Arithmetic & Broadcasting (Intro)

Notebook: **“Part 3: Arithmetic & Broadcasting”** markdown + empty “Your code here” cell.

- Concept (lightweight):
  - Elementwise arithmetic on arrays (no explicit loops)
  - Idea of broadcasting with scalars (e.g., `arr * 2`, `arr + 10`)
- Live coding into the Part 3 code cell:
  - Create a small 2D array and apply:
    - Scalar operations (add, multiply)
    - Elementwise operations between arrays of the same shape
- Learner activity:
  - Modify numbers, try a different scalar, and predict results before running

---

## Guided Practice 2

Notebook: Extend Part 3’s “Your code here” cell with simple tasks.

- Suggested prompts (typed by instructor into the cell / markdown above):
  - Create a 2D “sales” array and apply percentage increases
  - Compute a “discounted” array using scalar subtraction
- Learners code their solutions and compare outputs

---

## Wrap-up and Exit Ticket

- Recap key skills tied directly to notebook sections:
  - Performance benchmark (Part 1)
  - ndarray basics: shape, dtype, ndim (Part 2)
  - Casting and basic dtypes (Data Types and Casting)
  - Simple arithmetic and the idea of broadcasting (Part 3, intro)

