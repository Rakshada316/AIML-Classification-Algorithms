# Comparative Analysis of Classification Algorithms

## Project Overview
This project implements and compares four machine learning classification algorithms using Python and the Iris dataset.

The algorithms used are:
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)
- Naive Bayes

## Objectives
- Implement four classification algorithms.
- Evaluate their performance using accuracy, precision, recall, F1-score, and log loss.
- Compare the results using tables and graphs.
- Understand the suitability of each algorithm for different classification tasks.

## Dataset
The Iris dataset is available in Scikit-learn. It contains 150 flower samples belonging to three classes: Setosa, Versicolor, and Virginica.

Each sample has four features:
- Sepal length
- Sepal width
- Petal length
- Petal width

The dataset is divided into training and testing sets using an 80:20 ratio.

## Technologies Used
- Python
- Google Colab
- Scikit-learn
- Pandas
- Matplotlib

## Performance Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Log Loss

## How to Run
1. Open the notebook `AIML_Classification_Assignment.ipynb`.
2. Click Open in Colab, or download the notebook and upload it to Google Colab.
3. Run the notebook cells in order.
4. View the performance table and graphs.

## Results
In the initial experiment, SVM and Naive Bayes achieved 96.67% accuracy, while Decision Tree and KNN achieved 93.33% accuracy.

SVM recorded the lowest log loss in the experiment. Results may vary with different library versions or experimental settings.

## Conclusion
The experiment compares four classification algorithms using common evaluation metrics. It demonstrates that different algorithms have different strengths and that the most suitable algorithm depends on the dataset and task requirements.