# Machine Learning for Regression
## Key Topics Covered

### 2.1 Car Price Prediction Project
- Introduction to the regression problem
- Understanding the dataset and business objective

### 2.2 Data Preparation
- Loading and cleaning data
- Handling missing values
- Normalizing column names and data types

### 2.3 Exploratory Data Analysis (EDA)
- Understanding data distributions
- Identifying patterns and correlations
- Visualizing relationships between features and target

### 2.4 Validation Framework
- Train/Validation/Test split (e.g., 60%/20%/20%)
- Importance of data shuffling with random seeds
- Preventing data leakage

### 2.5 Linear Regression (Simple)
- Understanding the linear relationship: `y = w₀ + w₁x`
- Finding optimal weights using simple formulas

### 2.6 Linear Regression (Vector Form)
- Matrix representation: `y = Xw`
- Working with multiple features simultaneously

### 2.7 Training Linear Regression - Normal Equation
- Mathematical solution: `w = (XᵀX)⁻¹Xᵀy`
- Computing weights without iterative methods

### 2.8 Baseline Model
- Creating a simple baseline for comparison
- Understanding model performance benchmarks

### 2.9 Root Mean Squared Error (RMSE)
- Evaluation metric for regression: `RMSE = √(mean((y_true - y_pred)²))`
- Understanding prediction errors

### 2.10 Validation with RMSE
- Evaluating model on validation dataset
- Comparing training vs validation performance

### 2.11 Feature Engineering
- Creating new features from existing ones
- Transformations (log, polynomial, etc.)

### 2.12 Categorical Variables
- One-hot encoding for categorical features
- Handling non-numeric data

### 2.13 Regularization
- Ridge Regression: Adding penalty term `r·I` to prevent overfitting
- Formula: `w = (XᵀX + rI)⁻¹Xᵀy`
- Choosing regularization parameter `r`

### 2.14 Tuning the Model
- Hyperparameter selection
- Cross-validation strategies

### 2.15 Using the Model
- Making predictions on new data
- Model deployment considerations

### 2.16 Summary
- Recap of key concepts
- Best practices