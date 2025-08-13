# Logistic Regression from Scratch

This project is a complete implementation of the Logistic Regression algorithm in Python, built from the ground up without using high-level machine learning libraries like Scikit-learn for the model itself. The goal is to provide a clear, step-by-step understanding of how the algorithm works, from the sigmoid function to gradient descent and model evaluation.

The model is trained on the classic **Iris dataset** to solve a binary classification problem: predicting whether a flower is an **Iris Setosa** or not, based on its sepal length and sepal width.

## Project Highlights

-   **Manual Implementation:** The core logic of the logistic regression model, including the sigmoid function and gradient descent optimization, is written in pure Python using NumPy for numerical operations.
-   **Exploratory Data Analysis (EDA):** Uses `pandas` and `matplotlib` to perform initial data analysis and visualize the relationship between the features and the target variable.
-   **Model Training:** The model is trained using **gradient descent**, a fundamental optimization algorithm.
-   **Model Evaluation:** The final model's performance is evaluated using accuracy on a dedicated test set.
-   **Visualization:** The project includes a visualization of the learned **decision boundary**, which provides a clear graphical representation of how the model separates the two classes.

## Getting Started

### Prerequisites

You'll need to have the following libraries installed on your machine:

```bash
pip install numpy pandas matplotlib scikit-learn
