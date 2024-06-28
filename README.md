# Project README

## Gzip-Based Text Sentiment Classification

Welcome to the Gzip-Based Text Sentiment Classification project! This project presents an implementation of the paper titled "Less is More: Parameter-Free Text Classification with Gzip." The implementation aims to validate the claims made in the paper by applying the Gzip compressor to text data for sentiment classification. The dataset utilized in this project contains reviews from popular platforms such as Amazon, IMDB, and Yelp.

### About the Project

The project explores the effectiveness of utilizing the Gzip compressor, specifically leveraging the length of the compressed string, in text classification tasks. The primary objective is to assess whether sentiment expressed in English sentences can be accurately determined using this approach. The claims made in the referenced paper were tested using various classifiers, including KNN, SVC, Decision Tree, Extra Tree, and Random Forest.

To ensure the validity of the results, the project includes essential data preprocessing steps, such as data cleaning and feature extraction, along with the training of multiple versions of models to identify the best-performing classifier.

### Paper Reference

The paper titled "Less is More: Parameter-Free Text Classification with Gzip" can be accessed via the following link: [Paper Link](https://arxiv.org/abs/2212.09410)

### Libraries Used

The project leverages the following libraries for implementation:

- Gzip
- scikit-learn (KNeighborsClassifier, NuSVC, DecisionTreeClassifier, ExtraTreeClassifier, RandomForestClassifier)
- Pandas
- NumPy

### Results

After thorough experimentation, all the implemented models exhibited promising performance. The results of each classifier are as follows:

- KNeighborsClassifier: 60%
- Support Vector Classifier (SVC): 74%
- ExtraTreeClassifier: 56%
- RandomForestClassifier: 64%

The Support Vector Classifier (SVC) came out as the most effective classifier, performing better than the KNeighborsClassifier which was used in the referenced paper.

Thank you for your interest.
