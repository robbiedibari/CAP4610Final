# Premier League Football Match Outcome Prediction

# Introduction

In the domain of sports analytics, predicting the outcomes of football matches is a challenging yet valuable task. It enables clubs to anticipate game results, assists bettors in decision-making, and enriches fan experiences. This project details the development of a machine learning model designed to predict the results of Premier League football matches, offering insights into team performance and match dynamics.

# Project Structure

    data/: Contains the dataset used for training and testing the models.
    notebooks/: Jupyter notebooks with the code for data preprocessing, model training, evaluation, and visualization.
    src/: Source code for the project.
    README.md: Project overview and instructions.

# Dataset

The dataset comprises match statistics from the Premier League spanning from the 2000 to 2022 seasons. Key features include:

    Match date and venue
    Team statistics (e.g., goals scored, goals conceded, points)
    Match result (win, draw, loss)

# Methodology

    Data Preprocessing:
        Data cleaning and handling of missing values.
        Encoding categorical variables.
        Feature engineering to create new predictive features.

    Model Development:
        Evaluated multiple models: Logistic Regression, Random Forest, Gradient Boosting.
        Optimized hyperparameters using Grid Search.
        Selected Gradient Boosting as the final model based on performance metrics.

    Model Evaluation:
        Assessed model performance using accuracy, precision, recall, and F1 score.
        Visualized feature importance, ROC curve, and confusion matrix.
        Used cross-validation to ensure model stability.

# Results

    Gradient Boosting Model:
        Accuracy: 69.00%
        Precision: 67.49%
        Recall: 81.47%
        F1 Score: 73.82%
        Cross-validation mean accuracy: 63.44% with a standard deviation of 1.04

# Features

    DiffPts: Difference in points between the two teams.
    H_vs_A_Goal_Scored_Diff: Home vs. Away Goal Scored Difference.
    ATP: Away Team Points.
    HTGD: Home Team Goal Difference.
    ATGD: Away Team Goal Difference.
    Points_Ratio: Ratio of points between home and away teams.
    HTP: Home Team Points.
    H_vs_A_Goal_Conceded_Diff: Home vs. Away Goal Conceded Difference.
    DiffFormPts: Difference in form points between the two teams.
    ATFormPts: Away Team Form Points.
    ATGC: Away Team Goals Conceded.
    HTGS: Home Team Goals Scored.
    HTGC: Home Team Goals Conceded.
    HTFormPts: Home Team Form Points.
    ATGS: Away Team Goals Scored.

# Visualizations

The project includes several visualizations to better understand the data and model performance:

    Distribution of Full-time Home and Away Goals.
    Box plots showing Home and Away Team Points vs. Match Result.
    Scatter plot of Home vs. Away Team Goal Difference.
    Feature importance in the optimized Gradient Boosting Model.
    ROC curve and confusion matrix for model evaluation.

# Future Work

    Incorporate real-time data for predictions.
    Explore more complex features and alternative modeling techniques such as deep learning.
    Further refine the model to improve prediction accuracy.

# Getting Started
# Prerequisites

    Python 3.x
    Jupyter Notebook
    Required Python libraries: pandas, scikit-learn, Matplotlib, Seaborn, numpy

# Installation

    Clone the repository:

    sh

git clone https://github.com/robbiedibari/CAP4610Final.git



# Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or suggestions.

# License

This project is licensed under the MIT License - see the LICENSE file for details.
