# Cedit Card Fraud Detection

Credit Card Fraud Detection using different ensemble- and data-sampling methodes on an unbalanced dataset to determine the fraudulent transactions.
## Dataset

The dataset used for this project is collected from Kaggle at https://www.kaggle.com/mlg-ulb/creditcardfraud. It consists of 284,807 transactions that occurred in 2 days, of which 492 are labelled as Fraud. This means that the dataset is highly unbalanced with only 0.172% accounting for the Fraud transactions. It consists of 31 features of which 28 (V1-V28) are the result of PCA transformation, due to confidentiality issues. The remaining features that are not transformed are ‘Time’ and ‘Amount’, which represent the seconds elapsed between each transaction and the first transaction in the dataset and, the transaction amount respectively. The ‘Class’ feature represents the label of the transaction with ‘1’ for a Fraud transaction and ‘0’ for a ‘Genuine’ transaction.
## Run Locally

Clone the project

```bash
  git clone https://github.com/DominikSch004/CreditCardFraudDetection.git
```

Go to the project directory

```bash
  cd CreditCardFraudDetection
```

Install the dependencies

```pip
  pip install -r requirements.txt
```