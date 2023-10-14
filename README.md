# End-to-end email-spam-classifier-new


## Introduction
Welcome to the SMS/Email Spam Detection Classifier project! This project is designed to help you detect spam in text messages and emails using various machine learning algorithms, such as Naive Bayes, Decision Tree, SVM, and more. The project's frontend is built using Streamlit, and the application is deployed on Heroku.

## Table of Contents
* Features
* Installation
* Usage
* Machine Learning Algorithms
* Frontend
* Deployment

### Features
* Detect spam in SMS and email messages.
* Choose from multiple machine learning algorithms for classification.
* User-friendly web interface using Streamlit.
* Easy deployment on Heroku.

### Installation
To get this project up and running, follow these steps:

#### Install the required dependencies.
pip install -r requirements.txt

#### Usage
Run the Streamlit app using the following command:
streamlit run app.py

Open a web browser and navigate to the URL displayed in the terminal.

Use the web interface to input SMS or email messages and choose a machine learning algorithm for classification.

Click the "Predict" button to detect if the message is spam or not.

Machine Learning Algorithms
This project provides several machine learning algorithms for spam classification, including:

Naive Bayes
Decision Tree
Support Vector Machine (SVM)
...
You can select the desired algorithm from the web interface for classification.

## Frontend
The frontend of this project is built using Streamlit, a Python library for creating web applications with minimal effort. Streamlit allows users to interact with the spam detection classifier through a user-friendly interface.

## Deployment
The application is deployed on Heroku, a cloud platform that makes it easy to deploy, manage, and scale web applications. To deploy the application on Heroku, follow these steps:

Sign up for a Heroku account.

Install the Heroku Command Line Interface (CLI).

Log in to your Heroku account using the CLI:

heroku login
Create a Heroku app:
heroku create your-spam-detector-app

Deploy the application to Heroku:
git push heroku master

Open the deployed app in your browser:
heroku open
