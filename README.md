# Ridge and Lasso Regression: Math and Code

This project is a **comprehensive deep dive into Ridge and Lasso regression**, covering:

- **Mathematical derivations** of cost functions and optimization methods.
- **By-hand implementations**:
    - Ridge: closed-form and gradient descent.
    - Lasso: coordinate descent.
- **Visual explanations** showing how regularization affects coefficient shrinkage and feature selection.
- **Comparison with scikit-learn** models to validate manual implementations.
- **Animations** illustrating how Lasso can shrink coefficients to zero.

## 📂 Contents

- `notebook.ipynb` — Full Jupyter Notebook including math, code, visualizations, and comparisons.
- `data/` — Kaggle House Prices dataset subset used for modeling.
- `images/` — Plots and animations generated to explain key concepts.

## 📝 Topics Covered

- Linear regression recap.
- Ridge regression:
    - Closed-form solution.
    - Gradient descent implementation.
- Lasso regression:
    - Why no closed-form solution.
    - Coordinate descent algorithm.
- How to choose the regularization parameter $\alpha$.
- Coefficient comparison across models.
- Visual and animated demonstrations of shrinkage and feature selection.

## 🔧 Dependencies

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `IPython` (for animation display in notebooks)

## 📊 Data

Data used:
- Kaggle House Prices: Advanced Regression Techniques
- [Link to dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

## 📚 Motivation

This project aims to bridge the gap between:
- **Mathematical theory** behind regularization.
- **Practical coding** and understanding of how Ridge and Lasso work.
- **Intuition-building visualizations** for learners and practitioners.

## 🔗 Related

- [My Linear Regression notebook — OLS vs Gradient Descent](https://github.com/MaxWienandts/Linear_Regression_OLS_vs_Gradient_Descent)
- [Medium article](https://medium.com/@maxwienandts/understanding-linear-regression-statistical-vs-machine-learning-approaches-08a5a5b04bbe)

## 👤 Author

**Max Wienandts**  
[LinkedIn](https://www.linkedin.com/in/max-wienandts/) • [Medium](https://medium.com/@maxwienandts) • [GitHub](https://github.com/MaxWienandts)
