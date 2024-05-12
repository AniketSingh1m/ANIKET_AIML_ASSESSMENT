# Machine Learning Forecasting Project

## Project Overview

This project focuses on forecasting sourcing costs using machine learning techniques. The goal is to accurately predict sourcing costs based on historical data and relevant features.

## Table of Contents

1. [Project Overview](#overview)
2. [Project Structure](#structure)
3. [Setup Instructions](#setup)
4. [Usage](#usage)
5. [Model Evaluation](#evaluation)
6. [Conclusion](#conclusion)
7. [License](#license)

## Project Structure

Add a brief description of the project structure here.

## Setup Instructions

Provide instructions on how to set up the project environment.

## Usage

Explain how to use the project and any important usage considerations.

## Model Evaluation

Discuss the evaluation of different machine learning models and why XGBoost was chosen as the best model.

### XGBoost Performance:

- Test R2 Score: XGBoost has the highest test R2 score of 0.4039 among all the models, indicating that it explains a significant portion of the variance in the data compared to other models.
- Test RMSE and MAE: XGBoost also performs well in terms of test RMSE (40.2144) and test MAE (29.2672), although these metrics are slightly higher than some other models like Random Forest and Random Forest + GridSearchCV.

### Advantages of XGBoost:

- Complexity Handling: XGBoost is known for handling complex relationships in data and can capture non-linear patterns effectively.
- Regularization: It incorporates regularization techniques to prevent overfitting, making it robust against noise and outliers in the dataset.
- Feature Importance: XGBoost provides insights into feature importance, allowing you to understand which features are most influential in predicting sourcing costs.

### Considerations:

- While LSTM also shows competitive performance, it's a deep learning model that might require more data, tuning, and computational resources compared to XGBoost.
- SVR + Gradient Boosting has a lower R2 score and higher RMSE/MAE compared to XGBoost, indicating that it may not capture the underlying patterns as effectively.

### Conclusion:

Based on the metrics and considerations mentioned above, XGBoost emerges as the best suitable model for predicting sourcing costs in your dataset. However, it's always a good practice to further fine-tune and validate the chosen model based on domain knowledge and additional evaluation criteria specific to your use case.

## Conclusion

Summarize the project's findings, conclusions, and next steps.

## License

Include information about the project's license and any other relevant legal details.
