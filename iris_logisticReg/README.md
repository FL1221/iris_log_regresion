# Iris Dataset Classification Project

## Overview  
This project demonstrates a basic classification workflow using the Iris dataset. The goal is to predict iris species (setosa, versicolor, virginica) based on sepal and petal measurements.

## Key Steps  
1. **Data Loading & Exploration**:  
   - Load the Iris dataset and analyze feature distributions.  
   - Visualize relationships between features and target classes using histograms, scatterplots, and pairplots.  

2. **Model Training**:  
   - Split data into training (80%) and testing (20%) sets.  
   - Train a logistic regression classifier.  

3. **Evaluation**:  
   - Achieved **93.3% accuracy** on the test set.  
   - Cross-validation accuracy: **97.3%**.  
   - Identified misclassified samples (4 out of 150).  

4. **Visualization**:  
   - Highlighted misclassifications in petal length vs. width plots.  
   - Most errors occur between versicolor and virginica, as expected.  

## Dependencies  
- Python 3.x  
- pandas, numpy, matplotlib, seaborn, scikit-learn

## Dataset
This project uses the [Iris dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html) provided by `scikit-learn`.

