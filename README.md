# Naive Bayes Classifier

Lab 1 for the Probability & Statistics course: a Naive Bayes classifier, implemented from scratch, that detects discriminatory tweets.

## Contents
- `Naive_Bayes_Classifier_PS_Lab1.ipynb`: the main notebook
- `data/discrimination/`: train and test datasets
- `stop_words.txt`: list of stop words

## Results (test set)
| Model   | Accuracy | Precision | Recall | F1    |
|---------|----------|-----------|--------|-------|
| Unigram | 0.960    | 0.848     | 0.523  | 0.647 |
| Bigram  | 0.950    | 1.000     | 0.289  | 0.449 |

The data is imbalanced (~93% neutral), so F1 is a more informative metric than accuracy.

## How to run
pip install pandas numpy matplotlib
jupyter notebook Naive_Bayes_Classifier_PS_Lab1.ipynb

Then click **Run All**.