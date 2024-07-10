# Churn Prediction Model

## Overview
This project aims to predict customer churn at a bank using supervised machine learning models. The model leverages various customer attributes to determine the likelihood of a customer exiting the bank.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling](#modeling)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
Customer churn is a critical metric for businesses, especially in the banking sector. Predicting churn can help banks take proactive measures to retain customers. This project builds a predictive model using supervised categorical models to forecast churn.

## Dataset
The dataset used for this project is `Churn_Modelling.csv`, which contains the following columns:
- **RowNumber**: Unique identifier for each row
- **CustomerId**: Unique identifier for each customer
- **Surname**: Customer's surname
- **CreditScore**: Customer's credit score
- **Geography**: Customer's location
- **Gender**: Customer's gender
- **Age**: Customer's age
- **Tenure**: Number of years the customer has been with the bank
- **Balance**: Account balance
- **NumOfProducts**: Number of bank products the customer is using
- **HasCrCard**: Whether the customer has a credit card
- **IsActiveMember**: Whether the customer is an active member
- **EstimatedSalary**: Estimated salary of the customer
- **Exited**: Whether the customer has exited the bank

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/churn-prediction-model.git
    ```

2. Navigate to the project directory:
    ```sh
    cd churn-prediction-model
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
To use the model, follow these steps:

1. Load the dataset:
    ```python
    import pandas as pd
    df = pd.read_csv('Churn_Modelling.csv')
    ```

2. Run the Jupyter Notebook to train the model:
    ```sh
    jupyter notebook CHURN_ML_MODEL.ipynb
    ```

3. Follow the steps in the notebook to preprocess the data, train the model, and make predictions.

## Modeling
The project uses the following steps to build the churn prediction model:
1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.
2. **Feature Selection**: Selecting relevant features for the model.
3. **Model Training**: Training various supervised learning models and tuning hyperparameters.
4. **Evaluation**: Evaluating model performance using appropriate metrics.

## Results
The results of the model are evaluated based on accuracy, precision, recall, and F1-score. Detailed results and model performance metrics are provided in the Jupyter Notebook.

## Contributing
Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first. You can submit issues or fork the project and create a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
- **Name**: Michael Yisa
- **LinkedIn**: [Michael Yisa](https://www.linkedin.com/in/michael-yisa-382a9b249)

Feel free to explore the project, raise issues, and contribute!
