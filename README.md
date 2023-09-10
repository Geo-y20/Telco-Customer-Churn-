# Telco Customer Churn Prediction

## Introduction

Welcome to the Telco Customer Churn Prediction project. This project is dedicated to predicting customer churn in the telecommunications industry, a vital task for businesses aiming to retain their customers and make data-driven decisions to reduce attrition rates.

## Dataset

The dataset used in this project can be found [here](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). It contains information about Telco customers, including demographics, service subscriptions, and customer churn status. The dataset consists of various features, encompassing both numerical and categorical variables.

### Data Preprocessing

To prepare the data for analysis, we undertook the following steps:

- **Handling Missing Values**: Identified and addressed missing values to ensure data integrity.
- **Encoding Categorical Variables**: Categorical variables such as 'gender,' 'contract type,' and 'payment method' were encoded into numerical values for model compatibility.
- **Scaling Numerical Features**: Numerical features were scaled to maintain a consistent range, thereby improving model performance.

## Exploratory Data Analysis (EDA)

During the exploratory data analysis (EDA) phase, we uncovered key insights, including:

- **Summary Statistics**: Computed basic statistics such as mean, median, and standard deviation for numerical variables.
- **Data Visualizations**: Created various visualizations such as histograms, box plots, and correlation matrices to better understand data distribution and relationships.
- **Churn Analysis**: Analyzed churn rates in relation to different customer attributes to identify potential patterns and trends.

## Model Building

We employed several machine learning models for churn prediction, including:

- **Logistic Regression**: A fundamental classification model used for predicting churn status.
- **Decision Tree Classifier**: Employed for modeling more complex decision boundaries.
- **LightGBM Classifier**: A gradient boosting model known for its efficiency and predictive power.

Hyperparameters and model configurations were fine-tuned to achieve the best performance.

## Model Evaluation

To assess model performance, we employed various metrics including:

- **Accuracy**: Measures the overall accuracy of the models in predicting churn.
- **Precision**: Evaluates the models' ability to correctly predict positive churn cases.
- **Recall**: Assesses the models' ability to capture all actual positive churn cases.
- **F1-Score**: A combination of precision and recall to measure the model's overall performance.
- **Confusion Matrices**: Visualizations of model predictions versus actual churn status.

## Conclusion

In conclusion, the Telco Customer Churn Prediction project successfully explored, preprocessed, and built predictive models to identify customers at risk of churning. Key findings and feature importance were discussed, providing valuable insights for the business to take targeted actions to reduce churn rates. Further enhancements and model improvements can be considered for future work.

## How to Use

To replicate the results and use the code, follow these detailed steps:

1. Clone the repository to your local machine using the following command:
gh repo clone Geo-y20/Telco-Customer-Churn-

2. Ensure you have the required Python libraries and dependencies installed by running:
pip install pandas numpy seaborn matplotlib scikit-learn lightgbm

3. Execute the provided Python script for data preprocessing, model building, and evaluation.

4. Refer to the documentation within the code for more specific instructions and customization options.

## Dependencies

To run the code, you will need the following Python libraries and dependencies:

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- lightgbm

## License

This project is licensed under [MIT].

## Author

Author: [George Youhana]
