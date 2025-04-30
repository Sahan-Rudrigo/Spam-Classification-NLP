# Spam-Classification-NLP
This repository contains a Python notebook that uses Natural Language Processing (NLP) techniques to classify SMS messages as either spam or ham (non-spam). It includes data loading, preprocessing, model training (using Naive Bayes), and evaluation

# SMS Spam Classifier

## Overview

This project implements a Natural Language Processing (NLP) based system to classify SMS messages as either spam or ham (non-spam).  It utilizes techniques such as text preprocessing, feature extraction with TF-IDF, and the Multinomial Naive Bayes algorithm to achieve accurate spam detection.

## Files

* `spam_classification.ipynb`:  Jupyter Notebook containing the Python code for the entire spam classification pipeline.
* `sample_data/spam.csv`:  The dataset used for training and testing the model.  It contains SMS messages labeled as 'spam' or 'ham'.

## Dependencies

The following Python libraries are required:

* pandas
* nltk
* scikit-learn

You can install them using pip:

```bash
pip install pandas nltk scikit-learn
