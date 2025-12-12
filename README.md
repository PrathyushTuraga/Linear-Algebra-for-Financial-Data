# Linear Algebra for Financial Data  
## Least Squares Regression on Stock Returns

This project demonstrates how **core linear algebra concepts** can be applied to real-world financial data using **least squares regression**.

The notebook formulates linear regression explicitly as a matrix equation **Ax = b** and solves it using linear algebra, not black-box machine learning libraries.

This is an **educational, beginner-friendly project** intended to bridge linear algebra theory and practical data analysis.

---

## What This Project Does

- Models **percentage price change (`change_pct`)** as a linear combination of market features
- Constructs a **design matrix (A)** and target vector (b)
- Solves an **overdetermined system** using the least-squares solution
- Interprets regression coefficients in a financial context

The focus is on **understanding**, not prediction performance.

---

## Why This Project Is Useful

If you are learning linear algebra and wondering:

- *Where does Ax = b show up in real problems?*
- *What does least squares actually do geometrically?*
- *How do regression coefficients relate to real data?*

This notebook answers those questions with a concrete financial example.

---

## Notebook File

linear_algebra_least_squares_finance.ipynb


Run the notebook top to bottom.  
Each step explains **both the math and the code**.

---

## Dataset

This project uses trending stock data from Yahoo Finance.

**Dataset source:**  
https://huggingface.co/datasets/ronantakizawa/trending-stocks-yahoo-finance

All credit for the dataset goes to the original creator.

---

## Environment Setup

### 1. Create a Conda Virtual Environment (Python ≥ 3.10)

conda create -n linear-algebra-finance python=3.10

conda activate linear-algebra-finance


### 2. Install Dependencies

This repository includes a requirements.txt file.

pip install -r requirements.txt

### 3. Open the Notebook

You can use:
- VS Code
- Cursor
- Any IDE that supports Jupyter Notebooks

Make sure to select the conda environment kernel
linear-algebra-finance when running the notebook.

### Key Concepts Covered
- Linear systems and matrix multiplication
- Overdetermined systems
- Least squares and projections
- Interpreting regression coefficients
- Bias (intercept) terms in linear models
No prior machine learning knowledge is required.

### Learning Credits

This project is inspired by concepts from:

Linear Algebra for Machine Learning and Data Science by DeepLearning.AI

https://learn.deeplearning.ai/specializations/mathematics-for-machine-learning-and-data-science/overview

### Notes and Limitations
- The model assumes linear relationships
- Features are not standardized
- No train/test split is used

These choices are intentional to keep the focus on linear algebra fundamentals, not model optimization.

### Who This Project Is For
- Beginners learning linear algebra
- Students applying math to real data for the first time
- Anyone curious how regression emerges from linear algebra
