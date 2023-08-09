# FAKE-NEWS-CLASSIFIER-USING-NLP

This project aims to create a classifier to identify fake news articles using the Multinomial Naive Bayes algorithm.
Table of Contents

    Installation
    Usage
    Dataset
    Model
    Contributing
    License

Installation
Prerequisites

    Python 3.x
    pip

Steps

    Clone the repository:

bash

git clone <repository-url>

    Navigate to the project directory:

bash

cd fake-news-classifier

    Install the required packages:

bash

pip install -r requirements.txt

Usage

    Train the model:

bash

python train.py

    Test the model:

bash

python test.py <path-to-test-data>

Dataset

The dataset used for this project contains labeled examples of real and fake news articles. Each article is represented as a bag-of-words vector and is labeled either 'REAL' or 'FAKE'.
Data Format

Each row in the dataset contains:

    Article ID
    Article Text
    Label ('REAL' or 'FAKE')

Model

This classifier uses the Multinomial Naive Bayes algorithm. The MultinomialNB implementation from the Scikit-learn library is used to train and test the model.
Feature Extraction

Text data is converted into numerical format using the CountVectorizer from Scikit-learn, which turns the content into a matrix of token counts.
Training and Evaluation

The dataset is split into training and test sets. The model is trained on the training set and evaluated on the test set.
Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page to contribute.
License

This project is licensed under the MIT License - see the LICENSE.md file for details.
