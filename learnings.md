# k-NN classifier Learnings

## 1. Chi-Square test to perform feature importance analysis for categorical variables

    - higher chi-score = more importance
    - based on observed and expected observations

## 2. kNN is a lazy learner

    - delays the process of generalizing from training data until query is made during prediction.
    - algorithm "learn" by storing training data and only perform computation when making prediction
    - this contrast with eager learners, which builds a model during training phase
    - in short, lazy learner = train during pred, eager learner = train during fit
