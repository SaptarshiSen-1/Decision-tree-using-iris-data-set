# Decision Tree on Iris Dataset 🌸🌳
# Project Overview

This project demonstrates the use of a Decision Tree Classifier on the famous Iris dataset. The Iris dataset is a classic dataset in machine learning that consists of measurements of iris flowers from three different species:

Setosa

Versicolor

Virginica

The goal is to classify the species of an iris flower based on its sepal length, sepal width, petal length, and petal width.

# Key Steps in the Project

Load the Dataset

Used scikit-learn’s built-in Iris dataset.

Converted it into a Pandas DataFrame for easy handling.

Added both numerical target labels and human-readable species names.

Data Visualization

Scatter Plots:

Sepal Length vs Sepal Width

Petal Length vs Petal Width

Histograms: Distribution of all four features to understand their spread.

Model Training

Trained a Decision Tree Classifier using Entropy (Information Gain) as the splitting criterion.

Limited tree depth to prevent overfitting and improve interpretability.

Model Evaluation

Split the dataset into training and testing sets (70%-30%).

Evaluated the model’s accuracy on the test data.

Decision Tree Visualization

Plotted the decision tree diagram showing:

Splitting features

Threshold values

Entropy and sample counts

Final class predictions

This helps us see how information gain drives the splitting process.

# Visualizations Included

Sepal Length vs Sepal Width scatter plot

Petal Length vs Petal Width scatter plot

Histograms of all features (distribution analysis)

Decision Tree diagram (information gain visualization)

# Learning Outcomes

Understanding of how decision trees work.

Importance of information gain (entropy) in feature selection.

Visual intuition of dataset distribution and model decisions.

Basics of data preprocessing, training, testing, and evaluation in ML workflows.

# Tools & Libraries

Python

NumPy – numerical operations

Pandas – data manipulation

Seaborn & Matplotlib – visualization

Scikit-learn – machine learning model and utilities

# Applications

Decision Trees are widely used because they are:

Easy to visualize and interpret

Handle both numerical and categorical data

Useful in classification and regression tasks

The Iris dataset is a beginner-friendly dataset that makes it easy to understand these concepts before applying them to real-world problems.
