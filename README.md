# Linear Regression from Scratch

This repository contains my first machine learning project.

When starting out with data science, it's very easy to just import a pre-built model from `scikit-learn`. For my first project, I wanted to avoid doing that. Instead, I built a multiple linear regression model completely from scratch using Python and NumPy so I could actually understand the math and mechanics happening under the hood.

### What's inside

Rather than focusing on building a massive application, I used this notebook to get a practical grip on core concepts:

* **Vectorization:** Translating algebraic formulas for cost functions and gradients into efficient NumPy matrix operations.

* **Gradient Descent:** Implementing the optimization loop to see how a model iteratively minimizes error.

* **Data Preprocessing:** Standardizing features manually, making sure to compute the mean and standard deviation strictly from the training data to avoid data leakage into the test set.

* **Multiple Prediction Graphs:** Visualizing the model's performance by plotting individual features against the target variable.

### Tech Stack

* Python 3

* NumPy & Pandas

* Jupyter Notebook

### Note

Since this is my first step into machine learning, the code is written with a focus on readability and my own learning process rather than production-level optimization. If you happen to look through the code and have any feedback on how I can improve, I’d be glad to hear it.