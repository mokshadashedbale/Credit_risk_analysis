# Logistic Regression Model for Credit Risk Assessment

This repository contains code for building a logistic regression model to assess credit risk based on the provided dataset. The model predicts whether a loan application will be approved or rejected using various features such as applicant information, loan amount, credit history, etc.

## Dataset

The dataset used for this project is named `creditrisk.csv`. It includes the following variables:

- Loan_ID: Unique identifier for each loan application.
- Gender: Gender of the applicant (Male/Female).
- Married: Marital status of the applicant (Yes/No).
- Dependents: Number of dependents.
- Education: Education level of the applicant (Graduate/Not Graduate).
- Self_Employed: Self-employed status of the applicant (Yes/No).
- ApplicantIncome: Income of the applicant.
- CoapplicantIncome: Income of the co-applicant.
- LoanAmount: Amount of the loan requested.
- Loan_Amount_Term: Term of the loan.
- Credit_History: Credit history of the applicant (1: Good, 0: Bad).
- Property_Area: Area of the property (Urban/Rural/Semiurban).
- Loan_Status: Target variable indicating loan approval status (Approved/Rejected).

## Model Building Process

The model building process involves the following steps:

1. **Data Cleaning**: Preprocessing the dataset to handle missing values and ensure consistency.

2. **Label Encoding**: Converting categorical variables into numerical format using label encoding.

3. **Sampling**: Balancing the dataset using techniques such as oversampling or undersampling to address class imbalance.

4. **Logistic Regression Model**: Building a logistic regression model using Python's scikit-learn library.

5. **Model Evaluation**: Evaluating the model's performance using appropriate metrics such as accuracy, precision, recall, and F1-score.

## Files Included

- `credit_risk_analysis.ipynb`: Jupyter notebook containing the code for data preprocessing, model building, and evaluation.
- `Creditrisk.csv`: The dataset used for model training and testing.
- `requirements.txt`: List of Python dependencies required to run the code.

## Usage

To replicate the analysis and build the logistic regression model:

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Open and run the `credit_risk_analysis.ipynb` notebook in a Jupyter environment.

## Results

The final model achieves an accuracy of 80.20% on the test dataset and demonstrates robust performance in predicting loan approval status.

## Contributors

- [Mokshada Shedbale](https://github.com/mokshadashedbale)

