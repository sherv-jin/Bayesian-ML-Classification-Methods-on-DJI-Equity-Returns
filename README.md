# Bayesian Machine Learning for Classification: Predicting Dow Jones Index (DJI) Equity Returns

This project explores several Bayesian and probabilistic classification methods to predict stock returns from the **Dow Jones Industrial Average (DJIA)** index. The goal is to build interpretable models that incorporate uncertainty in their predictions using Bayesian inference techniques and gauge it's accuracy against one another

### Classification Methods Used:

| Method                                                  | Type                     | Inference Technique                            | Description                                                                 |
|---------------------------------------------------------|--------------------------|--------------------------------------------------|-----------------------------------------------------------------------------|
| **Logistic Regression**                                 | Frequentist              | Maximum Likelihood Estimation (MLE)             | Baseline classifier using the logistic (sigmoid) function                   |
| **Bayesian Logistic Regression**                        | Bayesian                 | Laplace Approximation                           | Approximates posterior around MAP with a Gaussian                          |
| **Bayesian Logistic Regression (ADVI)**                 | Bayesian                 | Automatic Differentiation Variational Inference | Scalable approximation of posterior using variational inference            |
| **Quadratic Discriminant Analysis (QDA)**               | Frequentist              | Closed-form                                     | Assumes Gaussian class-conditional densities with different covariances    |
| **Naïve Bayes Classifier**                              | Probabilistic Generative | Closed-form                                     | Assumes feature independence given the class                               |
| **Gaussian Process Classification**                     | Bayesian Nonparametric   | Variational / Laplace / Expectation Propagation | Flexible, kernel-based model with uncertainty estimates                    |
