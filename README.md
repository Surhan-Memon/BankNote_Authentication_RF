# BankNote_Authentication_RF
What if a machine could instantly tell whether a banknote is real or fake?

This project explores exactly that — using Machine Learning to build a highly accurate system that classifies banknotes with ~99% accuracy. Simple idea, powerful results.

Project Overview

In this project, we use a Random Forest model to distinguish between authentic and forged banknotes based on statistical features extracted from images.

The goal is not just accuracy — but understanding how data, models, and decisions come together to solve a real-world problem.

Dataset

Each banknote is represented using numerical features derived from image processing:

Variance
Skewness
Curtosis
Entropy

These features capture patterns that help the model differentiate between real and fake notes.

Data Exploration

Before training the model, we explored relationships between features using visualizations.

This step revealed an important insight:
The data is well-separated, making it ideal for classification tasks.

Model & Optimization

We trained a Random Forest Classifier, a powerful ensemble method that combines multiple decision trees.

To improve performance, we applied hyperparameter tuning, testing different combinations to find the most effective setup.

Along the way, we encountered and resolved real-world issues — like parameter compatibility — which added to the learning experience.

Results

The final model achieved:

Accuracy: ~99%
Only 2 misclassifications out of 200+ samples
Strong precision, recall, and F1-score across both classes

This shows the model is not only accurate but also reliable.

Insights
Increasing the number of trees improves performance — but only up to a point
The model generalizes well to unseen data
Even simple features can lead to excellent results when used effectively
What I Learned

This project strengthened my understanding of:

How ensemble models like Random Forest work
The importance of hyperparameter tuning
Debugging model constraints and warnings
Evaluating model performance beyond just accuracy
Why This Project Matters

Fraud detection is a critical real-world problem.
This project demonstrates how machine learning can contribute to building secure and intelligent systems — even with relatively simple data.

Future Improvements
Experiment with other models like SVM or Neural Networks
Improve feature engineering
Deploy this as a real-time application
