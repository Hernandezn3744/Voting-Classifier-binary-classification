# Voting-Classifier-binary-classification
Voting Classifier (binary classification)

We create a voting classifier using 21 classifiers from scikit-learn library using breast cancer data. We then train the classifiers, test the models performance using accuracy, precision, recall, f1 score, total number of misclassified predictions and show this information as a pandas DataFrame. This is done by creating a series of python functions that allow us to streamline the training and testing portion.

Project Overview- The program allows the user to use the VotingClassifier model with 21 classifiers.

Installation- You’ll need the ability to open the ‘.ipynb’ file. I found it easier to open the document by importing the file to Kaggle.com since it has an online notebook with the necessary libraries needed to run the program such as Tensorflow, Sci-Kit learn, and pandas.

Usage- Once you upload the file, simply hit run. If you’d like to run the program using a different dataset you’ll need to fit and transform your data using the appropriate “scaler” as well as cleaning your data, etc.

Data- The program uses data pre cleaned and prepared by Sci-kit learn under their “datasets” module.

Models- There are 21 different classifiers used to train the VotingClassifier model. However, before this we train/test and score each of the 21 models and display them as a pandas DataFrame with each column as its appropriate metric, and model name.

Results- The VotingClassifer preformed well with a precision of 97% with a little to no overfitting, or underfitting.


