IMDB Dataset Classification using Naive Bayes (Multinomial)

This repository is created as part of the iNeuBytes virtual internship program[June_2023]. It contains the code and resources for classifying movie reviews from the IMDB dataset using the Naive Bayes classification algorithm, specifically the Multinomial Naive Bayes variant. The aim of this project is to develop a model that can accurately predict whether a given movie review is positive or negative based on the text content.

Dataset

The IMDB dataset is a popular benchmark dataset for sentiment analysis. It consists of 50,000 movie reviews, split evenly into training and testing sets. Each review is labeled as either "positive" or "negative". The dataset is balanced, with an equal number of positive and negative reviews.

You can download the dataset from IMDB website or from other reliable sources such as Kaggle or the UCI Machine Learning Repository.

Prerequisites

To run the code, you need to have the following dependencies installed:
  Python (version 3.6 or higher)
  scikit-learn library

You can install the required libraries using the following command:
      pip install scikit-learn

Usage

Clone this repository to your local machine or download the source code as a ZIP file.
Navigate to the project directory.

Training the Model

Predicting Sentiment

Enter a movie review when prompted, and the model will predict the sentiment (positive or negative) of the review based on the trained model.

Results and Evaluation
The performance of the Naive Bayes classifier can be evaluated using metrics such as accuracy, precision, recall, and F1-score. These metrics indicate how well the model predicts the sentiment of movie reviews. The evaluation results can be found in the project documentation or can be implemented using the appropriate scikit-learn functions.

Future Enhancements

Explore advanced preprocessing techniques, such as word embeddings or n-grams, to improve the model's performance.
Optimize the hyperparameters of the Naive Bayes classifier for better results.
Consider using ensemble methods or other advanced classification algorithms to further enhance the sentiment prediction accuracy.
Incorporate domain-specific features, such as movie genre or director, to improve the model's understanding of the data.
