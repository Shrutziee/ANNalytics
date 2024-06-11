<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Predicting Customer Churn Using Artificial Neural Networks</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        h1, h2, h3 {
            color: #333;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            margin-bottom: 10px;
        }
        .results {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
        }
        .results pre {
            margin: 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Project Description: Predicting Customer Churn Using Artificial Neural Networks</h1>
        <p>This project aims to predict customer churn using an Artificial Neural Network (ANN) model. Customer churn refers to customers who stop doing business with a company. The ability to accurately predict churn can help businesses proactively retain customers and improve their services. Here's a detailed description of the project:</p>
        
        <h2>Objective</h2>
        <p>The primary goal of this project is to build and evaluate an ANN to predict whether a customer will exit (churn) based on various features from the dataset.</p>
        
        <h2>Dataset</h2>
        <p>The dataset used in this project is a customer churn dataset, which includes various features such as:</p>
        <ul>
            <li><strong>CreditScore:</strong> Customer's credit score.</li>
            <li><strong>Geography:</strong> Customer's country.</li>
            <li><strong>Gender:</strong> Customer's gender.</li>
            <li><strong>Age:</strong> Customer's age.</li>
            <li><strong>Tenure:</strong> Number of years the customer has been with the bank.</li>
            <li><strong>Balance:</strong> Customer's account balance.</li>
            <li><strong>NumOfProducts:</strong> Number of products the customer has with the bank.</li>
            <li><strong>HasCrCard:</strong> Whether the customer has a credit card.</li>
            <li><strong>IsActiveMember:</strong> Whether the customer is an active member.</li>
            <li><strong>EstimatedSalary:</strong> Customer's estimated salary.</li>
            <li><strong>Exited:</strong> Whether the customer has churned (1) or not (0).</li>
        </ul>
        
        <h2>Summary of Results</h2>
        <div class="results">
            <h3>Confusion Matrix</h3>
            <pre>
array([[1551,   56],
       [ 237,  156]])
            </pre>
            <h3>Accuracy Score</h3>
            <p>0.8535 indicates the proportion of correctly classified instances.</p>
        </div>
    </div>
</body>
</html>
