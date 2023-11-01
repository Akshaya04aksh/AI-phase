# AI-phase

# Diabetes Prediction System

## Overview
This is an AI-based diabetes prediction system that uses machine learning algorithms to predict the likelihood of an individual developing diabetes. The system analyzes medical data, including features like glucose levels, blood pressure, BMI, etc., and provides early risk assessment and personalized preventive measures.

## Dependencies
Before running the code, make sure you have the following dependencies installed:

- Python (3.6+)
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook (optional, for running Jupyter notebooks)

You can install these dependencies using `pip`:
```
pip install pandas numpy scikit-learn jupyter
```

## Data
The dataset used for this project can be found on Kaggle:
[Diabetes Dataset on Kaggle](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)

1. Download the dataset and save it as `diabetes_data.csv` in the project directory.

## Running the Code
To run the code and train the diabetes prediction model, follow these steps:

1. Clone or download this project from the repository.

2. Install the required dependencies as mentioned in the "Dependencies" section.

3. Make sure the `diabetes_data.csv` file is in the project directory.

4. Open and run the Jupyter notebook `Diabetes_Prediction.ipynb` to execute the code step by step. Alternatively, you can run the Python script using the command:
```
python diabetes_prediction.py
```

5. The model will be trained and evaluated, and you will see the evaluation metrics displayed in the console.

## Model Evaluation
The model is evaluated using various metrics, including:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

These metrics are used to assess the model's performance in predicting diabetes.

## Future Improvements
- Feature engineering: Explore additional feature engineering techniques to enhance prediction accuracy.
- Hyperparameter tuning: Experiment with different hyperparameters and optimization techniques to optimize the model's performance.
- Deployment: Consider deploying the model as a web application or API for real-time predictions.
