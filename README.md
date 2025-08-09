📧 Email Spam Detection
Python, Scikit-Learn & NLP
This project uses Natural Language Processing (NLP) and Machine Learning to classify emails as spam or ham (not spam) based on their text content. By applying TF-IDF vectorization and a Logistic Regression model, the system learns patterns in email messages and can predict the category for new incoming emails.

📷 Features
Reads and processes an email dataset (mail_data.csv).

Cleans and prepares the text data for machine learning.

Uses TF-IDF Vectorization to convert text into numerical features.

Trains a Logistic Regression classifier to identify spam emails.

Achieves over 96% accuracy on test data.

Allows user to input custom email text for real-time spam prediction.

🧠 How It Works
Data Loading – Import the dataset containing labeled emails (spam/ham).

Preprocessing – Replace null values, convert labels (spam → 0, ham → 1).

Feature Extraction – Apply TF-IDF Vectorizer to transform text into feature vectors.

Model Training – Train a Logistic Regression model on the processed data.

Evaluation – Measure model accuracy on training and test sets.

Prediction – Input a custom email message and predict whether it’s spam or not.

🧰 Requirements
Python 3.x

pandas

scikit-learn

Install dependencies:

bash
Copy
Edit
pip install pandas scikit-learn
