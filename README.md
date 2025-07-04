# ML Algorithms from Scratch: Linear Regression and Beyond

This repository contains basic implementations of foundational machine learning algorithms built from scratch using Python and NumPy.

---

## Part 1: Linear Regression

### 1. Least Mean Squares (LMS) Algorithm

Gradient descent update rule:

**LMS Update Rule**:  
θ := θ - α · ∂J(θ)/∂θ

### 2. Normal Equation

θ = (XᵗX)⁻¹Xᵗy

### 3. Locally Weighted Linear Regression (LWLR)

Weight for each training example:

**LWLR Weight**: 

wᵢ = exp(-((xᵢ - x_query)ᵗ(xᵢ - x_query)) / (2τ²))

Weighted normal equation:

θ = (XᵗWX)⁻¹XᵗWy

Prediction:

ŷ = x_queryᵗθ

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
