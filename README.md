# Coding-samurai-task-1

Project Description:

In this project, i will create a simple machine learning model to predict the species of flowers based on their features. You can use the famous Iris dataset, which contains measurements of four features (sepal length, sepal width, petal length, and petal width) for three different species of iris flowers (setosa, versicolor, and virginica). .
Objective and Approach:
The goal was to develop a model using the Iris dataset to predict the species of Iris flowers, choosing among setosa, versicolor, and virginica based on their sepal and petal dimensions. The K-Nearest Neighbors (KNN) classifier was selected for this task. Given the initial promising results, we also delved into hyperparameter tuning to possibly refine the model's performance.

Model Performance (Before Tuning): The model demonstrated outstanding results on the test set:

Accuracy: 100.00%

Precision, Recall, and F1-score for each class (setosa, versicolor, virginica): All metrics reached the maximum score of 1.00, showcasing flawless precision, recall, and F1-score.

Hyperparameter Tuning: We underwent a hyperparameter tuning process using grid search to potentially enhance the model. The model's performance remained impeccable, suggesting that the initial parameters were already near-optimal for this dataset.

Predictions on New Data:

For a flower with measurements [5.1, 3.5, 1.4, 0.2], the model confidently determined its species as Iris-setosa. Another flower, with measurements [8.1, 2.5, 2.4, 0.0], was classified as Iris-versicolor.

Conclusion: Using the KNN classifier, we achieved a 100% accuracy on the Iris dataset, correctly predicting species like Iris-setosa and Iris-versicolor from new data. Hyperparameter tuning confirmed that initial parameters were near-optimal. Despite the perfect score, it's crucial to test the model on diverse real-worlld data to ensure its broad applicability and robustness.

Project Documentation: Iris Flower Classification
1. Objective: Classify Iris flowers into three species (setosa, versicolor, virginica) based on sepal and petal measurements using the K-Nearest Neighbors (KNN) classifier.

2. Data Acquisition: Source: UCI Machine Learning Repository. Attributes: Sepal length, sepal width, petal length, petal width, species.

3. Data Preprocessing: Split data into features (X) and target (y). Divided data into training (80%) and test sets (20%) using stratified sampling.

4. Model Selection and Training: Model: K-Nearest Neighbors (KNN) classifier. Training: Used fit
