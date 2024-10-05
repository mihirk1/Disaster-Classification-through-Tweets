# Disaster-Classification-through-Tweets

This repository contains the Disaster Tweet Classifier, a machine learning project that utilizes a pre-trained BERT model from Hugging Face’s transformers library to classify tweets as related to disasters or not. This project is structured to handle separate datasets for training and testing the model.

Project Structure

	•	train.csv: CSV file containing the training data with tweets and their labels.
	•	test.csv: CSV file containing the testing data with tweets.
	•	disaster_tweet_classifier.py: Main Python script for training the model and evaluating it on the test dataset.

Dependencies

This project requires Python 3.x and several dependencies listed below:

	•	pandas
	•	re
	•	nltk
	•	transformers
	•	torch
	•	matplotlib

Setup

Before running the project, ensure that you have Python installed on your system. You can then install the required Python packages using the following command: pip install pandas nltk transformers torch matplotlib

Usage

	1.	Prepare Your Dataset:
	•	Ensure you have train.csv with columns text and label for training data.
	•	Ensure you have test.csv with a text column for testing data.
	2.	Running the Script:
	•	Upload the Python script and CSV files to a Jupyter environment like Google Colab.
	•	Run the script by following the on-screen instructions to upload your train.csv and test.csv when prompted.
	3.	Output:
	•	The script will train a BERT model on the training data and output predictions for the test data.
	•	It will also generate a pie chart showing the distribution of disaster versus non-disaster tweets in the test set.
