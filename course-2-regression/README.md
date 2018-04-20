### What is regression?
- From features to predictions
    - `Data` -> input x: features derived from data -> `Regression`
    - `Regression`: Learn x -> y relationship -> `Intelligence`
    - `Intelligence`: continuous "output" or "response" to input

### Module 1: Simple Regression
- What makes it simple?
    - **1 input** and just **fit a line** to data
- Define **goodness-of-fit** metric for each possible line
- **Gradient descent algorithm**
- **Get estimated parameters**
    - interpret
    - use to form predictions

### Module 2: Multiple Regression
- Fit **more complex relationships** than just a line
- Incorporate more inputs

### Module 3: Assessing Performance
- Overfit
- Measures of error:
    - Training
    - Test
    - True (generalization)
- Bias-variance tradeoff

### Module 4: Ridge Regression
- **Ridge total cost =**
    - **measure of fit + measure of model complexity**
    - bias-variance tradeoff
- How to choose balance? (i.e., model complexity)
    - **Cross validation**

### Module 5: Feature Selection & Lasso Regression
- Useful for **efficiency** of predictions and **interpretability**
- **Lasso total cost =**
    - **measure of fit + (different) measure of model complexity**
    - **knocks out certain features... "sparsity"**
    - Coordinate descent algorithm

### Module 6: Nearest Neighbor & Kernel Regression
- Find the most similar one to mine

### Summary of what's covered
`Models`
- Linear regression
- Regularization: Ridge (L2), Lasso (L1)
- Nearest neighbor and kernel regression

`ALgorithms`
- Gradient descent
- Coordinate descent

`Concepts`
- Loss functions, bias-variance tradeoff, cross-validation
- sparsity, overfitting, model selection, feature selection
