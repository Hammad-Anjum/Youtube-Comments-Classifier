#YouTube Comments Classifier
##Overview:
The "YouTube Comments Classifier" project focuses on collecting comments from specified YouTube channels, cleaning and preprocessing the data, and then using machine learning and deep learning models to predict labels for these comments. The project consists of three main files: scrap.py, clean.py, and model.py.

##scrap.py:

Description: The scraping script uses Selenium and BeautifulSoup to collect comments from predefined YouTube channels. It also performs data cleaning, language filtering, and exports the data to CSV files.

##clean.py:
Description: This file cleans and preprocesses the collected comments, applying techniques such as spell checking, lemmatization, and language filtering. The cleaned data is saved to a new CSV file.

##model.py:
Description: The model script implements and evaluates machine learning (Logistic Regression and Naive Bayes) and deep learning (RNN and CNN) models for comment classification. It compares the models using accuracy scores and confusion matrices, displaying the results through various charts.

##Model Performance:
Logistic Regression: 70% accuracy
Naive Bayes: 67% accuracy
RNN: 45% accuracy
CNN: 52% accuracy
