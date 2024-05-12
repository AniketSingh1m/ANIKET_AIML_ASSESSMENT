<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Machine Learning Forecasting Project</title>
</head>

<body>

    <h1>Machine Learning Forecasting Project</h1>

    <h2>Project Overview</h2>
    <p>This project focuses on forecasting sourcing costs using machine learning techniques. The goal is to accurately predict sourcing costs based on historical data and relevant features.</p>

    <h2>Table of Contents</h2>
    <ol>
        <li><a href="#overview">Project Overview</a></li>
        <li><a href="#structure">Project Structure</a></li>
        <li><a href="#setup">Setup Instructions</a></li>
        <li><a href="#usage">Usage</a></li>
        <li><a href="#evaluation">Model Evaluation</a></li>
        <li><a href="#conclusion">Conclusion</a></li>
        <li><a href="#license">License</a></li>
    </ol>

    <h2 id="structure">Project Structure</h2>
    <p>Add a brief description of the project structure here.</p>

    <h2 id="setup">Setup Instructions</h2>
    <p>Provide instructions on how to set up the project environment.</p>

    <h2 id="usage">Usage</h2>
    <p>Explain how to use the project and any important usage considerations.</p>

    <h2 id="evaluation">Model Evaluation</h2>
    <p>Discuss the evaluation of different machine learning models and why XGBoost was chosen as the best model.</p>
    <ul>
        <li><strong>XGBoost Performance:</strong></li>
        <ul>
            <li>Test R2 Score: XGBoost has the highest test R2 score of 0.4039 among all the models, indicating that it explains a significant portion of the variance in the data compared to other models.</li>
            <li>Test RMSE and MAE: XGBoost also performs well in terms of test RMSE (40.2144) and test MAE (29.2672), although these metrics are slightly higher than some other models like Random Forest and Random Forest + GridSearchCV.</li>
        </ul>
        <li><strong>Advantages of XGBoost:</strong></li>
        <ul>
            <li>Complexity Handling: XGBoost is known for handling complex relationships in data and can capture non-linear patterns effectively.</li>
            <li>Regularization: It incorporates regularization techniques to prevent overfitting, making it robust against noise and outliers in the dataset.</li>
            <li>Feature Importance: XGBoost provides insights into feature importance, allowing you to understand which features are most influential in predicting sourcing costs.</li>
        </ul>
        <li><strong>Considerations:</strong></li>
        <ul>
            <li>While LSTM also shows competitive performance, it's a deep learning model that might require more data, tuning, and computational resources compared to XGBoost.</li>
            <li>SVR + Gradient Boosting has a lower R2 score and higher RMSE/MAE compared to XGBoost, indicating that it may not capture the underlying patterns as effectively.</li>
        </ul>
        <li>Conclusion: Based on the metrics and considerations mentioned above, XGBoost emerges as the best suitable model for predicting sourcing costs in your dataset. However, it's always a good practice to further fine-tune and validate the chosen model based on domain knowledge and additional evaluation criteria specific to your use case.</li>
    </ul>

    <h2 id="conclusion">Conclusion</h2>
    <p>Summarize the project's findings, conclusions, and next steps.</p>

    <h2 id="license">License</h2>
    <p>Include information about the project's license and any other relevant legal details.</p>

</body>

</html>
