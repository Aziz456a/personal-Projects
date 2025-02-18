# Spam NLP Classifier

# Spam Classification Project

## Overview

This project focuses on developing a Natural Language Processing (NLP) model to accurately classify text messages as either "Spam" or "Ham" (non-spam). Utilizing a dataset of approximately 6,000 messages from Kaggle, the project encompasses data exploration, preprocessing, model development, and performance evaluation.

## Table of Contents

- [Data Exploration](#data-exploration)
- [Data Preprocessing](#data-preprocessing)
- [Model Development](#model-development)
- [Handling Class Imbalance](#handling-class-imbalance)
- [Evaluation Metrics](#evaluation-metrics)
- [Conclusion](#conclusion)
- [References](#references)

## Data Exploration

Initial data exploration involved:

- **Class Distribution Analysis**: Identified a significant imbalance between spam and ham messages.
- **Message Length Examination**: Analyzed the distribution of message lengths to understand text characteristics.
- **Frequent Terms Identification**: Determined common words and phrases in each class.

## Data Preprocessing

A robust preprocessing pipeline was established to clean and prepare the data:

1. **Lowercasing**: Standardized text by converting all characters to lowercase.
2. **Tokenization**: Split text into individual words or tokens.
3. **Stop Words Removal**: Eliminated common words that do not contribute significant meaning.
4. **Punctuation and Special Characters Removal**: Stripped out non-alphanumeric symbols.
5. **Stemming and Lemmatization**: Reduced words to their root forms to handle variations.

## Model Development

The modeling phase included:

- **Feature Extraction**: Converted text data into numerical representations using techniques like TF-IDF.
- **Model Creation** : Created a custom LSTM Model.
- **Training and Validation**: Split data into training and validation sets to assess model performance.

## Handling Class Imbalance

To address the class imbalance:

- **Undersampling**: Reduced the number of ham messages to match the spam count.
- **Oversampling**: Duplicated spam messages to balance the dataset.
- **Synthetic Data Generation**: Applied techniques like SMOTE to create synthetic examples of the minority class.

## Evaluation Metrics

Model performance was evaluated using:

- **Accuracy**: Overall correctness of the model.
- **Precision**: Proportion of true positive predictions among all positive predictions.
- **Recall**: Proportion of true positive predictions among all actual positives.
- **F1-Score**: Harmonic mean of precision and recall.

## Conclusion

The project successfully developed an NLP model capable of accurately classifying spam and ham messages. Key takeaways include:

- The importance of thorough data preprocessing.
- Effective strategies for handling class imbalance.
- The value of iterative model evaluation and refinement.

## References

- [Kaggle SMS Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset)
- [Scikit-learn: Machine Learning in Python](https://scikit-learn.org/)
- [NLTK: Natural Language Toolkit](https://www.nltk.org/)

