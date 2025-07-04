# ML Algorithms from Scratch: Linear Regression and Beyond

This repository contains basic implementations of foundational machine learning algorithms built from scratch using Python and NumPy.

---

## Part 1: Linear Regression

### 1. Least Mean Squares (LMS) Algorithm

Gradient descent update rule:

\[
\theta := \theta - \alpha \cdot \frac{\partial J(\theta)}{\partial \theta}
\]

### 2. Normal Equation

\[
\theta = (X^T X)^{-1} X^T y
\]

### 3. Locally Weighted Linear Regression (LWLR)

Weight for each training example:

\[
w^{(i)} = \exp\left( -\frac{(x^{(i)} - x_{query})^T(x^{(i)} - x_{query})}{2\tau^2} \right)
\]

Weighted normal equation:

\[
\theta = (X^T W X)^{-1} X^T W y
\]

Prediction:

\[
\hat{y} = x_{query}^T \theta
\]

*Not implemented yet:* Probabilistic Interpretation

---

## Coming Soon

**Part 2: Classification and Logistic Regression**
- Logistic Regression  
- Perceptron Learning Algorithm  

**Part 3: Generalized Linear Models**
- Exponential Family  
- Constructing GLM  
- Assumption Regression  
- Softmax Regression  

**Part 4: Generative Learning**
- Gaussian Discriminant Analysis  
- Naive Bayes  

**Part 5: Support Vector Machines**
- Functional Margin  
- Geometric Margin  
- Optimal Margin Classifier  

---

## Requirements

- Python 3.8+
- NumPy
- Matplotlib (optional)

## License

This project is licensed under the MIT License.
