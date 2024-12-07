## Objective: Mastering k-Nearest Neighbours (k-NN)

## 1. Theoretical Mastery

### 1.1 Classification using k-NN

    - assign class labels based on majority class of k-nearest neighbours
    - tie-breaking technique for cases of equal class distribution

### 1.2 Regression with k-NN

    - predicts continuous value by averaging value of k nearest neighbours

### 1.3 Distance metrics

    - Euclidean distance: Common distance metric for continuous variables
    - Mahattan distance: Sum of absolute difference between points
    - Minkowski distance: Generalization of both Euclidean & Manhattan
    - Cosine similarity: Measures angle between vectors (text classification)

### 1.4 Curse of Dimensionality

    - performance of kNN can degrade in high-dimensional spaces as "nearnesss" becomes less meaningful

---

## 2. Algorithmic Mastery

### 2.1 k-NN for Classification

    - implement k-NN classfier from scratch
    - identify k-NN and predict the majority class

### 2.2 k-NN for Regression

    - implement k-NN regressor from scratch
    - predict average values of k-nearest neighbours

### 2.3 Optimize Distance Calculation & use libraries

    - use data structures like KD-Trees, Ball-Trees for efficient nearest neighbour search
    - use library implementation for k-nearest-neighbours

---

## 3. Performance Analysis

### 3.1 Classification Metrics

    - Accuracy | Precision | Recall | F1-Score

### 3.2 Regression Metrics

    - MAE | MSE | RMSE

### 3.3 Finding optimal k

    - small k = sensitive to noise & overfitting
    - large k = soother decision boundaries but may underfit

---

## 4. Advanced k-NN techniques

### 4.1 Weighted k-NN

    - assign weights to neighbours based on distance
    - closer neighbours have more influence

### 4.2 Dimensionality Reduction

    - use PCA / t-SNE to reduce data dimensions and combat curse

### 4.3 Efficient Data Structures

    - use KD-Trees & Ball Trees for faster nearest neighbour search

### 4.4 Custom Distance Metric

    - use custom distance metric that reflect true underlying structure of data to improve accuracy
