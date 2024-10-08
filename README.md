# Predicting The Churn Probability of Customers Given the Historical Behaviour in a Telco Company

This project focuses on predicting the probability of customer churn based on their historical behavior in a telecommunications company. Using machine learning techniques, we analyze a Telco customer dataset to determine whether customers are likely to churn.

## Telco Churn Dataset

The dataset contains information about customers from a telecommunications company, including various features related to their demographics, account information, and service usage. The objective is to predict whether a customer will churn (i.e., leave the service).

### Data Source

The dataset used in this project is publicly available on Kaggle:

- [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Machine Learning Models

Three machine learning models were used for churn prediction in this project:
1. **Decision Tree**
2. **Random Forest (without hyperparameter tuning)**
3. **Random Forest (with hyperparameter tuning)**

### Model Performance

#### Recall (Sensitivity):
- **Decision Tree**: 0.51
- **Random Forest (without hyperparameter tuning)**: 0.46
- **Random Forest (with hyperparameter tuning)**: 0.40

#### Precision:
- **Decision Tree**: 0.46
- **Random Forest (without hyperparameter tuning)**: 0.61
- **Random Forest (with hyperparameter tuning)**: 0.68

#### ROC AUC (Receiver Operating Characteristic - Area Under Curve):
- **Decision Tree**: 0.67
- **Random Forest (without hyperparameter tuning)**: 0.83
- **Random Forest (with hyperparameter tuning)**: 0.86

### Final Model
The final model chosen for the project was the **Decision Tree** classifier, with the following performance metrics:
- **Recall**: 51%
- **Precision**: 46%

## Conclusion

This project demonstrates the ability of various machine learning models to predict customer churn in a telecom setting. Although hyperparameter tuning improved the performance of the Random Forest model in terms of precision and ROC AUC, the Decision Tree model was selected for its balance between recall and precision.

## Usage

To run this project locally, clone the repository and follow these steps:
1. Install the required dependencies.
2. Load the dataset from the provided Kaggle link.
3. Run the Jupyter Notebook or Python scripts to train the models and evaluate their performance.

```bash
git clone https://github.com/your-username/churn-prediction.git
cd churn-prediction
pip install -r requirements.txt
