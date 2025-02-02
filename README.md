# MACHINE-LEARNING-MODEL-IMPLEMENTATION.
# API-INTEGRATION-AND-DATA-VISUALIZATION

**COMPANY NAME** :CODTECH IT SOLUTIONS

**NAME** :N.Hima Bindu Aparna

**INTERN ID** :CT08LGO

**DOMINE** : PYTHON

**BATCH DURATION** :January 10th, 2025 to February 10th, 2025.

**MENTOR NAME** :Neela Santhosh Kumar 

**output** :https://github.com/aparnanelapolu/MACHINE-LEARNING-MODEL-IMPLEMENTATION./edit/main/README.md

**discription** : 1. Importing Libraries:

pandas is used for data manipulation and analysis.
io is used for working with input and output streams.
requests is used for making HTTP requests (downloading the dataset).
zipfile is for working with zip archives.
2. Loading the Dataset:

It downloads the "SMS Spam Collection" dataset from the UCI Machine Learning Repository.
The dataset is a zip file, which is extracted to get the SMSSpamCollection file.
This file is then read into a pandas DataFrame, with columns named "label" and "message".
3. Preprocessing:

The "label" column is converted to binary values: 0 for "ham" (not spam) and 1 for "spam".
The data is split into features (X, the message text) and the target variable (y, the label).
4. Splitting Data:

The dataset is split into training and testing sets using train_test_split.
80% of the data is used for training and 20% for testing.
5. Feature Extraction (TF-IDF):

TfidfVectorizer is used to convert text messages into numerical representations.
It calculates the importance of words in the messages.
6. Model Training:

A MultinomialNB (Naive Bayes) model is created.
The model is trained using the TF-IDF features and the corresponding labels from the training data.
7. Prediction:

The trained model is used to predict the labels for the test data.
8. Evaluation:

The model's performance is evaluated using metrics like accuracy and a classification report.
A confusion matrix is also generated to visualize the performance.
9. Testing with New Messages:

A list of new messages is created.
These messages are transformed into TF-IDF format.
The model predicts whether each new message is spam or ham.
The predictions are printed.
