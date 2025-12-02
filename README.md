# Customer Churn Prediction

## Project Overview

This project predicts customer churn for a telecommunications company. The goal is to identify customers who are likely to leave (churn) based on their account information and usage patterns. By predicting churn early, the company can take actions to retain customers and improve overall satisfaction.

## Dataset

The dataset contains customer information and includes the following files:

* `churn_data.csv` – Original customer dataset
* `synthetic_churn_data.csv` – Synthetic dataset for testing and experimentation

Key columns include:

* `SeniorCitizen` – Whether the customer is a senior citizen (0 = No, 1 = Yes)
* `tenure` – Number of months the customer has stayed with the company
* `MonthlyCharges` – Monthly subscription charges
* `TotalCharges` – Total charges for the customer
* `Churn` – Target variable (Yes = customer churned, No = customer stayed)

## Project Structure

```
Customer_Churn_Prediction/
│
├── data/                  # Dataset files
│   ├── churn_data.csv
│   └── synthetic_churn_data.csv
│
├── notebooks/             # Jupyter notebooks
│   ├── churn_analysis.ipynb  # Exploratory Data Analysis (EDA) and modeling
│   ├── Untitled.ipynb
│   └── Untitled1.ipynb
│
└── README.md              # Project description and instructions
```

## Tools and Libraries

* Python 3.x
* pandas
* numpy
* scikit-learn
* seaborn
* matplotlib
* imbalanced-learn (for handling class imbalance)

## Steps Performed

1. **Data Loading & Cleaning:** Import CSV, check missing values, convert data types.
2. **Exploratory Data Analysis (EDA):** Visualize churn distribution and analyze key features.
3. **Feature Engineering:** Handle categorical variables and scaling if necessary.
4. **Model Training:** Trained models such as Logistic Regression, Decision Tree, and Random Forest.
5. **Evaluation:** Used accuracy, confusion matrix, and classification report to evaluate models.
6. **Handling Imbalanced Data:** Applied SMOTE for oversampling minority class to improve model performance.
7. **Visualization:** Plotted feature importance and churn distribution.

## Usage

1. Clone the repository:

   ```
   git clone https://github.com/Mubashir12143/Customer_Churn_Prediction.git
   ```
2. Navigate to the project folder:

   ```
   cd Customer_Churn_Prediction
   ```
3. Open Jupyter Notebook:

   ```
   jupyter notebook
   ```
4. Run `churn_analysis.ipynb` to see full analysis and model predictions.

## Results

* Baseline model achieved an accuracy of ~0.67.
* After handling class imbalance with SMOTE, model performance can be further improved.
* Confusion matrices and classification reports are available in the notebook.
* Visualizations provide insights into churn patterns.

## Notes

* Dataset is included in the repository.
* Model performance depends on dataset size and feature selection.
* For real-world applications, a larger and more representative dataset is recommended.

## Author

**Mubashir Saeed**
GitHub: [https://github.com/Mubashir12143](https://github.com/Mubashir12143)
