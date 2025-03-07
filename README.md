# Iris Flower Classification Project

This project demonstrates how to perform classification on the classic Iris dataset using several machine learning models. It includes steps for data exploration, model training with GridSearchCV, model evaluation with cross-validation, and prediction visualization on new data. Various visualizations (e.g., confusion matrix heatmaps, count plots, boxplots, violin plots, and prediction probability bar charts) help to interpret the model's performance.

## Overview

The project covers:
- **Data Exploration:**  
  Load and inspect the Iris dataset. Visualize relationships between features and species using pair plots, boxplots, violin plots, and count plots.
  
- **Model Training & Hyperparameter Tuning:**  
  Train multiple models (Logistic Regression, Decision Tree, Random Forest, SVM) using GridSearchCV to find the best hyperparameters.
  
- **Model Evaluation:**  
  Evaluate models on a hold-out test set, compute confusion matrices, and generate classification reports.
  
- **Cross-Validation:**  
  Perform 10-fold cross-validation to ensure robust performance estimation.
  
- **Prediction on New Data:**  
  Predict the species of new flower measurements and visualize the prediction probabilities.
  
- **Visualization:**  
  Visualize counts, distributions, and prediction confidence levels using Seaborn and Matplotlib.


## Requirements

The project is implemented in Python and requires the following libraries:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn


## Usage

1. **Data Exploration:**  
   Run the data exploration section in `main.py` to load the Iris dataset and visualize the distribution of species and feature relationships.

2. **Model Training & Evaluation:**  
   - The project trains multiple models using GridSearchCV to optimize hyperparameters.
   - Evaluate the models on a test set and display the confusion matrix and classification report.
   - Perform cross-validation on the best model to get robust performance estimates.

3. **Prediction on New Data:**  
   - Provide new flower measurements (e.g., via a NumPy array).
   - Convert the input data into a DataFrame with proper feature names.
   - Predict the species and visualize the predicted probabilities using bar charts.

4. **Visualization:**  
   The project includes various plots:
   - **Count Plot:** Shows the count of each Iris species.
   - **Boxplots and Violin Plots:** Visualize the distribution of features across species.
   - **Confusion Matrix Heatmap:** Visualizes model performance on the test set.
   - **Prediction Probabilities Bar Chart:** Visualizes the model's confidence in its predictions on new data.


## Customization

Feel free to modify:
- **Hyperparameters:** Edit the parameter grids in the GridSearchCV section.
- **Visualization Settings:** Adjust plotting styles and labels to suit your needs.
- **Models:** Add or remove models as desired.

## Conclusion

This Iris Flower Classification project provides a complete workflow—from data exploration and model tuning to evaluation and prediction visualization. It serves as a template for building and interpreting classification models on small, well-known datasets.

For any questions or suggestions, please contact Muhammed John at +212 647-466-338.
