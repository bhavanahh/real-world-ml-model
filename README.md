# Cancer Survival Prediction Using Machine Learning

## Project Overview

This project explores a cancer dataset and applies machine learning classification models to predict the survival label provided in the dataset.

The project demonstrates data cleaning, exploratory data analysis, preprocessing, model training, evaluation, and comparison.

**Note:** This is an educational project. The dataset and model have not been validated for clinical use and must not be used for medical decisions.

## Dataset

The dataset contains information such as:
- Age
- Gender
- Country
- Cancer stage
- Family history
- Smoking status
- BMI
- Cholesterol level
- Other health-related variables
- Diagnosis year
- Survival label

The data was checked for missing values, duplicate rows, and invalid or extreme values.

## Machine Learning Models

The following classification models were evaluated:

1. Logistic Regression
2. Random Forest
3. Extra Trees

The data was split into training and testing sets using an 80:20 ratio.

## Evaluation Metrics

The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

The models were compared to identify the strongest result based on the selected evaluation metric.

## Results

The best model in the current evaluation was **Logistic Regression**, selected based on F1-score.

The classification report showed:
- Accuracy: 52%
- F1-score for class 0: 0.64
- F1-score for class 1: 0.29

These results indicate that the model has limited predictive performance, particularly for the survival class.

## Project Structure

```text
cancer-survival-prediction/
├── cancer_survival_prediction.ipynb
├── requirements.txt
├── README.md
└── outputs/
    ├── model_comparison.png
    └── predictions.csv
```

## How to Run

1. Clone or download this repository.
2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook cancer_survival_prediction.ipynb
   ```

4. Update the dataset path if necessary and run the notebook cells.

## Limitations

- The model has low predictive performance for the survival class.
- The dataset contains missing and suspicious values that require careful handling.
- The results depend on the quality and reliability of the dataset.
- This project is for learning and experimentation only, not clinical use.

## Author

Bhavana B