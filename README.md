# Python-Data-Science-ML-Classification

Structure:

Initially, an exploratory analysis (Python-Jupyter Notebook) is presented to highlight key relationships between multiple features/variables of different data types (numerical,categorical/object) that are included in a 'Bank Loan Status' dataset (.csv file format). The analysis enables the identification of meaningful insights for predicting whether an individual that wants to apply for a loan will be capable of paying it back or not.

In addition, a demonstration of Data Preprocessing is also provided to a) handle efficiently possible missing values/entries with respect to each dataset feature and b) modify the categorical features in order to be inserted as ML model inputs(independent variables) during the neural network training process (dropping features/creating dummy variables where applicable)

Finally, a Deep Learning model (neural network) is constructed that takes the selected bank loan features as model inputs for training purposes,'learns' the key relationships between input-output training data and predicts whether or not a new customer will be capable of paying back the acquired loan.

The evaluation of the ML neural network model performance is based on its ability to classify (successfully or not) whether the Loan Status of an individual will be 'Fully Paid' or 'Charged off', (classification_report-confusion matrix metrics) and this is why 90% of the data are to be used for network training and 10% for validation purposes.

The Dataset (.csv file format) for this project has been obtained from Kaggle:

"Bank Loan Status Dataset" -- File: "credit_test.csv" -- Source: https://www.kaggle.com/zaurbegiev/my-dataset
