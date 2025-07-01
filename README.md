Spam Email Classifier
This project builds a simple spam email classifier using Naive Bayes and Scikit-learn. The model predicts whether an email is spam based on its content.

Overview
Uses basic email text data for classification.

Applies text vectorization using CountVectorizer.

Trains a Naive Bayes model to classify emails as spam (1) or not spam (0).

Evaluates the model's accuracy.

Technologies Used
Python

Scikit-learn

How It Works
A small dataset of email samples is created.

CountVectorizer converts email text into numerical feature vectors.

The data is split into training and testing sets.

A Naive Bayes model (MultinomialNB) is trained on the training data.

The model predicts on the test data.

The accuracy of the model is printed.

How to Run
Install dependencies:

nginx
Copy
Edit
pip install scikit-learn
Run the Python script:

nginx
Copy
Edit
python spam_email_classifier.py
The model will output the accuracy of the spam classification.

Sample Output
makefile
Copy
Edit
Accuracy: 1.0
