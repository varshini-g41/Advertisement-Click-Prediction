# ONLINE ADVERTISEMENT CLICK PREDICTION USING RANDOM FOREST CLASSIFIER

## 1. PROJECT OVERVIEW

Online Advertisement Click Prediction is a Machine Learning project developed to predict whether a user is likely to click on an online advertisement based on their demographic information and online browsing behavior.

The project uses the Random Forest Classification algorithm to analyze user data and classify advertisement interactions into two categories: Clicked (1) and Not Clicked (0).

The main objective is to demonstrate how machine learning techniques can be applied to digital advertising data for predictive analysis and classification.

## 2. PROJECT OBJECTIVES

- To analyze online advertising user data.
- To understand user behavior and advertisement interactions.
- To perform data exploration and preprocessing.
- To identify important features influencing advertisement clicks.
- To train a Random Forest classification model.
- To predict whether a user will click an advertisement.
- To evaluate model performance using standard classification metrics.
- To visualize prediction results and model performance.

## 3. TECHNOLOGIES AND LIBRARIES USED

**Programming Language:**
- Python

**Development Environment:**
- Google Colab
- Jupyter Notebook

**Python Libraries:**
- Pandas – Data loading and manipulation.
- NumPy – Numerical computations.
- Matplotlib – Data visualization.
- Seaborn – Statistical visualization.
- Scikit-learn – Machine learning model development and evaluation.

## 4. DATASET DESCRIPTION

The project uses the Advertising Dataset containing 1,000 records and 10 attributes.

The dataset consists of the following attributes:

1. Daily Time Spent on Site – Time spent by a user on the website.
2. Age – Age of the user.
3. Area Income – Average income of the user's geographical area.
4. Daily Internet Usage – Daily internet usage of the user.
5. Ad Topic Line – Topic or description of the advertisement.
6. City – City of the user.
7. Male – Gender indicator (0 or 1).
8. Country – Country of the user.
9. Timestamp – Date and time of the advertisement interaction.
10. Clicked on Ad – Target variable indicating whether the advertisement was clicked (0 or 1).

For model training, five input features are selected:

- Daily Time Spent on Site
- Age
- Area Income
- Daily Internet Usage
- Male

The target variable is Clicked on Ad.

## 5. DATA PREPROCESSING

The following preprocessing operations are performed:

- Loading the dataset using Pandas.
- Examining dataset structure and data types.
- Checking missing values.
- Checking duplicate records.
- Selecting relevant input features.
- Separating input variables and target variables.
- Dividing the dataset into training and testing sets.

The City, Country, Ad Topic Line and Timestamp attributes are excluded from the initial model.

## 6. MACHINE LEARNING ALGORITHM

### Random Forest Classifier

Random Forest is a supervised machine learning algorithm used for classification and regression tasks.

It works by creating multiple decision trees and combining their predictions to produce a final result.

In this project, the Random Forest Classifier predicts whether a user will click an online advertisement based on selected user attributes.

**Model Configuration:**
- Algorithm: Random Forest Classifier.
- Number of Estimators: 100.
- Random State: 42.
- Training Data: 80%.
- Testing Data: 20%.

## 7. MODEL EVALUATION

The model performance is evaluated using the following metrics:

- **Accuracy:** Measures the overall correctness of predictions.
- **Precision:** Measures the proportion of predicted clicks that are actually clicks.
- **Recall:** Measures the proportion of actual clicks correctly identified.
- **F1-Score:** Represents the harmonic mean of precision and recall.

**Recorded Model Evaluation Results:**

- Accuracy: 97.00%
- Precision: 97.00%
- Recall: 97.00%
- F1-Score: 97.00%

The results indicate that the Random Forest model achieved 97% on all four evaluation metrics on the test dataset.

## 8. DATA VISUALIZATIONS

The project includes the following visualizations:

1. Advertisement Click Distribution – Displays the distribution of clicked and non-clicked advertisements.
2. Correlation Heatmap – Shows the correlation between selected numerical features.
3. Confusion Matrix – Displays correct and incorrect classification results.
4. Model Performance Graph – Compares Accuracy, Precision, Recall and F1-Score.
5. Feature Importance Graph – Identifies the relative importance of input features.
6. ROC Curve – Evaluates classification performance at different thresholds.
7. Actual vs Predicted Comparison – Compares actual outcomes with predicted outcomes.
8. Precision-Recall Curve – Illustrates the relationship between precision and recall.

These visualizations help understand the dataset, model behavior and prediction performance.

## 9. PROJECT FILE STRUCTURE

Advertisement-Click-Prediction/

    |
    |-- Advertisement_Click_Prediction.ipynb
    |
    |-- advertising.csv
    |
    |-- README.md

### File Description

- Advertisement_Click_Prediction.ipynb: Contains the complete Python code, data exploration, preprocessing, model training, predictions, evaluation metrics and visualizations.
- advertising.csv: Contains the online advertising user records used for model training and testing.
- README.md: Provides project information, objectives, dataset description, methodology and execution instructions.

## 10. HOW TO RUN THE PROJECT

Step 1: Download the project notebook and dataset.

Step 2: Open Google Colab (https://colab.research.google.com/).

Step 3: Upload the Advertisement_Click_Prediction.ipynb notebook.

Step 4: Run the initial cell and upload advertising.csv when prompted.

Step 5: Execute the notebook cells sequentially.

Step 6: Observe the dataset analysis, model training, predictions, evaluation metrics and visualizations.

## 11. EXPECTED OUTPUT

After executing the notebook, the project displays:

- Dataset information and preprocessing results.
- Training and testing dataset information.
- Random Forest model predictions.
- Confusion Matrix.
- True Positive, True Negative, False Positive and False Negative values.
- Accuracy, Precision, Recall and F1-Score.
- Feature Importance Graph.
- ROC Curve.
- Precision-Recall Curve.
- Actual vs Predicted Comparison.

## 12. CONCLUSION

The Online Advertisement Click Prediction project demonstrates the application of supervised machine learning for digital advertising classification.

The Random Forest Classifier is trained using user-related attributes to predict advertisement-click behavior.

The model achieved 97% accuracy, precision, recall and F1-score on the test dataset. The project also uses different evaluation metrics and visualizations to analyze the performance of the trained model.

This project provides practical experience in data preprocessing, machine learning model development, classification, performance evaluation and data visualization using Python.

## 13. DISCLAIMER

This project is developed strictly for educational and academic purposes. The predictions are based on the available dataset and should not be considered a guarantee of actual user behavior.
