# Toxic_Comment_Classification

Dataset: https://drive.google.com/file/d/1xNzvONLQiIFePgXDCFRnnyTnBDaZBEJr/view?usp=sharing

The goal of this project is to create a classifier model that can predict if input text is inappropriate (toxic).
1.	Exploratory Data Analysis: This is done by loading all the dataset. Firstly, we will check if there are any missing values in the dataset. Then we count the number of comments under each label and also the number of comments having multiple labels.
2.	Data Pre-processing:  Here we first clean the data by removing html-tags, punctuation etc. Next, we remove all the stop-words present in the comments. Then we do stemming. After that we will split the dataset into train and test sets. Then we will compute TF-IDF.
3.	Multi-label classification: Here we will train and test our model using different classifiers such as One vs Rest classifier, Binary Relevance, Classifier Chains , and calculate their accuracies and classification reports.


BY - ANJALI SHARMA

ROLL NO. - 102015140

SUBGROUP- ENC6
