# KNN Diabetes Prediction Project

## Overview
This project uses the K-Nearest Neighbors (KNN) algorithm to predict whether a person has diabetes based on various health metrics. The dataset used is from the [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database), which contains medical data from a population of women of Pima Indian heritage.

## Dataset
- **Pregnancies**: Number of times pregnant.
- **Glucose**: Plasma glucose concentration.
- **BloodPressure**: Diastolic blood pressure (mm Hg).
- **SkinThickness**: Triceps skinfold thickness (mm).
- **Insulin**: 2-Hour serum insulin (mu U/ml).
- **BMI**: Body mass index (weight in kg/(height in m)^2).
- **DiabetesPedigreeFunction**: Diabetes pedigree function.
- **Age**: Age in years.
- **Outcome**: Class variable (0 or 1) indicating whether the patient has diabetes.

## Requirements
- Python 3.x
- Pandas
- Scikit-learn
- Jupyter Notebook (optional for running the notebook)

## Steps to Run the Project
1. **Clone the repository**: 
   ```bash
   git clone <repository-url>


2.**Load and Preprocess the Data**:

The dataset is loaded and features are scaled to ensure they are on the same scale.

3.**Train the Model**:

The KNN model is trained using a grid search to find the optimal hyperparameters.

4.**Evaluate the Model**:

The model's performance is evaluated using metrics like accuracy and F1 score.

5.**Make Predictions**:

The model is used to predict whether a new patient has diabetes based on their health metrics.

## Results
The best accuracy achieved was approximately 81.82% with a corresponding F1 score.
Confusion Matrix: Shows the number of correct and incorrect classifications.
The project demonstrates the application of KNN in a medical dataset, providing insights into the possibility of predicting diabetes based on health indicators.

## Improvements
Hyperparameter Tuning: Additional fine-tuning can be done to further improve model accuracy.
Feature Engineering: New features could be created to capture more complex patterns in the data.
Ensemble Methods: Combining KNN with other algorithms may yield better results.

## License
This project is licensed under the MIT License - see the LICENSE file for details.


