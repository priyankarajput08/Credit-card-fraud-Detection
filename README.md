Credit Card Fraud Detection 💳

This project uses Machine Learning to detect fraudulent credit card transactions.

📌 Project Overview

Credit card fraud detection is a classification problem where transactions are classified as:

- 0 → Genuine Transaction
- 1 → Fraudulent Transaction

The dataset contains 284,807 transactions with 31 columns.

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

🔍 Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Checked the first few rows using "head()".
3. Checked dataset shape using "shape".
4. Checked missing values.
5. Checked duplicate records.
6. Analyzed genuine and fraudulent transactions.
7. Examined transaction amount statistics.
8. Separated features ("X") and target ("y").
9. Split the dataset into training and testing data.
10. Used stratified splitting to maintain the class distribution.

🤖 Machine Learning Algorithm

Decision Tree Classifier

A Decision Tree Classifier was trained to classify transactions as genuine or fraudulent.

📊 Model Evaluation

The model was evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score

These metrics help understand how well the model detects fraudulent transactions, especially because fraud transactions are much fewer than genuine transactions.

📁 Project Files

- "credit_card_fraud.ipynb" — Jupyter Notebook containing the complete project
- "creditcard.csv" — Dataset used for the project

🎯 Learning Outcomes

Through this project, I learned:

- Basic data preprocessing
- Handling and understanding imbalanced datasets
- Feature and target separation
- Train-test splitting
- Stratified data splitting
- Decision Tree classification
- Model evaluation
- Confusion matrix
- Precision, Recall and F1-score

🚀 Future Improvements

- Try additional classification algorithms.
- Apply feature selection.
- Handle class imbalance using suitable techniques.
- Compare different models using precision, recall and F1-score.
- Improve fraud detection performance.
