# Kickstarter

## Goal

Course project for "Data Mining" university course.

## Data

- [Kaggle link](https://www.kaggle.com/datasets/iamsajanbhagat/kickstarter)

## Plan of Attack

- [X] Load data.
- [X] Data audit and information value analysis.
- [X] Feature Engineer: use date columns to make durations (in load data notebook).
- [X] Finish univariate analysis.
- [X] PyCaret without text features.
- [X] Move missing value handling to first notebook.
- [X] Restructure code.
- [X] Save PyCaret models plots with performance analysis.
- [X] Make regressor for number of backers.
- [X] Add chi-sq.
- [X] Make regressor for log transform number of backers.
- [X] Evaluate model.
- [X] Use regressor and classifier on test set.
- [ ] Check if adding text features improves performance.
  - [ ] One-hot encode cateogircal features.
  - [ ] Scale numbers.
- [ ] Use GloVE or an alternative to embed text.
- [ ] Pass resulting matrix to pretrained BERT and use the "Trainer" class.
- [ ] Experiment with HDBSCAN to check for a pattern for the target variable.
- [ ] Start documentation.

## Resources

- [Predicting the success of crowdfunding](https://cs230.stanford.edu/projects_spring_2018/reports/8289614.pdf)
- [PyCaret Classification API](https://pycaret.readthedocs.io/en/stable/api/classification.html)
- [PyCaret Regression API](https://pycaret.readthedocs.io/en/stable/api/regression.html)
- [PyCaret Workflow](https://towardsdatascience.com/introduction-to-binary-classification-with-pycaret-a37b3e89ad8d)
- [Box-Cox Transform](https://towardsdatascience.com/top-3-methods-for-handling-skewed-data-1334e0debf45)
