# k-NN classifier Learnings

## 1. Chi-Square test to perform feature importance analysis for categorical variables

    - higher chi-score = more importance
    - based on observed and expected observations

## 2. kNN is a lazy learner

    - delays the process of generalizing from training data until query is made during prediction.
    - algorithm "learn" by storing training data and only perform computation when making prediction
    - this contrast with eager learners, which builds a model during training phase
    - in short, lazy learner = train during pred, eager learner = train during fit

## 3. Scikit-learn libraries trained much quicker

    1. distance calculations in scikit learn uses vectorized operations, which are faster.

    2. brute-force search in custom implementation is O(N * M) whereas scikit-learn uses KD-Tree and Ball-Tree which reduces complexity of finding nearest neighbours

    3. scikit-learn uses parallelization whereas custom code uses serial processing
