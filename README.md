# Credit Risk Assessment Project

## Overview

The Credit Risk Assessment project aims to develop a machine learning model to predict the risk associated with lending to borrowers. The model classifies loan applications as either **approved** or **rejected** based on various financial parameters. This project utilizes logistic regression to assess the likelihood of default, enabling financial institutions to make informed lending decisions.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Data](#data)
- [Model Evaluation](#model-evaluation)
- [Contributing](#contributing)
- [Application](#application)

## Features

- Predicts loan approval status based on borrower financial attributes.
- Uses logistic regression for classification.
- Evaluation metrics such as accuracy, precision, recall, and F1-score to assess model performance.
- User-friendly interface for dynamic input testing.

## Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib (for visualization)
- Jupyter Notebook (for development)

## Data

The dataset used for this project includes various features related to loan applications, such as:

- **loan_size**: The amount of money requested by the borrower.
- **interest_rate**: The interest rate applied to the loan.
- **borrower_income**: The annual income of the borrower.
- **debt_to_income**: The ratio of the borrower's debt to their income.
- **num_of_accounts**: The number of accounts the borrower has.
- **derogatory_marks**: The number of derogatory marks on the borrower's credit report.
- **total_debt**: The total debt of the borrower.
- **loan_status**: The target variable indicating loan approval (1) or rejection (0).

The dataset can be found in the `data` directory of the project.

## Model Evaluation

Model accuracy was 99.38%. 

- **True Negatives (14921)**: The model correctly predicted 14921 instances as Negative (0).
- **False Positives (89)**: The model incorrectly predicted 89 instances as Positive (1), which were actually Negative (0).
- **False Negatives (7)**: The model incorrectly predicted 7 instances as Negative (0), which were actually Positive (1).
- **True Positives (491)**: The model correctly predicted 491 instances as Positive (1).

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to add features, please fork the repository and submit a pull request.

## Application 

To test user input predictions, use the input section in the notebook to enter financial parameters. The model will dynamically process the input data and output whether the loan is likely to be approved or rejected. This allows users to simulate various loan scenarios and understand how different financial attributes impact the likelihood of approval, enhancing the overall user experience and providing valuable insights for decision-making.
