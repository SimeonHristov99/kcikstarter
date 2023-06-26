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
- [ ] Make regressor for number of backers.
- [ ] Use regressor and classifier on test set.
- [ ] Change MI to information gain, information value, chi-sq or document frequency.
- [ ] Separate toolbox files into their own package.
- [ ] Research how you can use toolbox without coping it every new project.
- [ ] One-hot encode cateogircal features.
- [ ] Scale numbers.
- [ ] Use GloVE or an alternative to embed text.
- [ ] Pass resulting matrix to pretrained BERT and use the "Trainer" class.
- [ ] Experiment with HDBSCAN to check for a pattern for the target variable.
- [ ] Start documentation.

## Icebox

- [ ] Try to learn word embeddings.
- [ ] Try to use Glove word embeddings.
- [ ] Text preprocessing: stopwords removal.
- [ ] Text preprocessing: convert numbers to their word equivalent.
- [ ] Text preprocessing: stemming.
- [ ] Text preprocessing: lemmatization.
- [ ] Text preprocessing: leave only words.
- [ ] Construct a tf-idf matrix.
- [ ] Try out an RNN with tf-idf matrix.
- [ ] Try out an RNN with Glove word embeddings.

## Resources

- [Predicting the success of crowdfunding](https://cs230.stanford.edu/projects_spring_2018/reports/8289614.pdf)
- [PyCaret Classification API](https://pycaret.readthedocs.io/en/stable/api/classification.html)
- [PyCaret Workflow](https://towardsdatascience.com/introduction-to-binary-classification-with-pycaret-a37b3e89ad8d)
- [Box-Cox Transform](https://towardsdatascience.com/top-3-methods-for-handling-skewed-data-1334e0debf45)
