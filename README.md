# sms-spam-classifier
SMS Spam Classifier
This is a machine learning project that aims to classify text messages as either spam or ham (not spam). It uses a Naive Bayes classifier trained on a dataset of SMS messages labeled as spam or ham.

Installation
Clone this repository to your local machine.
Install the required packages listed in the requirements.txt file. You can use the following command: pip install -r requirements.txt.
Usage
To use the SMS Spam Classifier, follow these steps:

Open your terminal and navigate to the project directory.
Run the main.py script using the command python main.py.
Enter the text message that you want to classify when prompted by the program.
The program will output whether the message is spam or ham.
Dataset
The dataset used to train the Naive Bayes classifier is the SMS Spam Collection dataset from the UCI Machine Learning Repository. It contains a collection of SMS messages that have been tagged as either spam or ham.

Preprocessing
The SMS messages in the dataset were preprocessed before being used to train the Naive Bayes classifier. The preprocessing steps included:

Removing punctuation and special characters.
Converting all letters to lowercase.
Removing stop words (common words like "the", "and", "a", etc. that do not add much meaning to a sentence).
Stemming the remaining words (reducing words to their root form).
Model Training
The Naive Bayes classifier was trained on the preprocessed SMS messages using the scikit-learn library in Python. The model achieved an accuracy of 98% on the test set.

Credits
This project was created by [Your Name]. Feel free to use and modify this project as you see fit. If you have any questions or suggestions, please feel free to contact
