# Penguin Classification Project

## Overview

This project aims to classify penguin species based on various physical attributes using machine learning techniques. The dataset used in this project contains information about the species, island, bill dimensions, flipper length, body mass, and sex of penguins.

## Dataset

The dataset used in this project is the famous 'penguins' dataset from the seaborn library. It consists of 344 entries and 7 columns. The columns include:

1. species
2. island
3. bill_length_mm
4. bill_depth_mm
5. flipper_length_mm
6. body_mass_g
7. sex

## Data Cleaning and Preprocessing

1. Handling Missing Values:
   - Removed rows with missing values using `df.dropna()`.

2. Encoding Categorical Variables:
   - Encoded categorical variables 'sex' and 'island' using one-hot encoding.

3. Feature Selection:
   - Selected relevant features for classification.

## Exploratory Data Analysis (EDA)

1. Checked unique values and distributions of categorical variables.

## Model Building

Two Random Forest classifiers were trained using different hyperparameters:

1. Model 1:
   - Number of Estimators: 5
   - Criterion: Entropy

2. Model 2:
   - Number of Estimators: 7
   - Criterion: Gini

## Model Evaluation

Both models were evaluated using the test set, and the following metrics were calculated:

- Confusion Matrix
- Classification Report
- Accuracy Score

## Results

### Model 1:
- Accuracy: 98%
- Precision: 0.98 (weighted average)
- Recall: 0.98 (weighted average)
- F1-score: 0.98 (weighted average)

### Model 2:
- Accuracy: 99%
- Precision: 0.99 (weighted average)
- Recall: 0.99 (weighted average)
- F1-score: 0.99 (weighted average)

## Conclusion

The Random Forest classifiers performed well in classifying penguin species based on the given attributes. Model 2, with hyperparameters n_estimators=7 and criterion='gini', showed slightly better performance with a 99% accuracy rate.

Feel free to use and contribute to this penguin classification project!
