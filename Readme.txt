 Number Recognition using Random Forest Classifier

## Description
This project involves building a random forest classifier to recognize handwritten digits from the MNIST dataset. The model achieves an accuracy of 98% and demonstrates the effective use of machine learning techniques for image recognition tasks. The project also includes hyperparameter tuning, evaluation metrics, and confusion matrix analysis.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Example Output](#example-output)
- [Evaluation Metrics](#evaluation-metrics)
- [Credits](#credits)

## Installation
1. Clone the repository:
   
   git clone https://github.com/yourusername/codingTasks.git

2. Navigate to the project directory:

    cd codingTasks/number-recognition
    
3. Install the required packages found at the top of the Notebook


Usage:

Run the program:

    python main.py

The program will:
    Load the digits dataset.

    Split the data into training and testing sets.

    Train a random forest classifier.

    Display sample images with their labels.

    Print the accuracy of the model.

    Perform hyperparameter tuning to find the optimal number of estimators.

    Print the accuracy scores for different values of n.

    Display a confusion matrix.

    Print evaluation metrics including precision, recall, and F1-score.



Example Output

Image Data Shape (1797, 64)
Label Data Shape (1797,)
Accuracy: 0.9722222222222222
Score of 0 with n of 0
Score of 0.963888 with n of 2
...
Confusion Matrix:
   0  1  2  3  4  5  6  7  8  9
0 33  0  0  0  0  0  0  0  0  0
1  0 37  0  0  0  0  0  0  0  0
...
Accuracy: 0.9722222222222222
Precision: 0.9731517282724029
Recall: 0.9716741532746081
F1-Score: 0.9719610479236171

Evaluation Metrics

    Accuracy: Measures the overall correctness of the model.
    Precision: Measures the accuracy of the positive predictions.
    Recall: Measures the ability of the model to find all the relevant cases.
    F1-Score: The harmonic mean of precision and recall.

Credits:
Developed by Jake Dinsdale.