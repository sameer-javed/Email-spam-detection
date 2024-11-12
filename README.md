# Email Spam Detection

This project focuses on building a machine learning model to classify emails as either "spam" or "not spam" based on the content. Using data collected from Kaggle, I applied various preprocessing steps, data transformations, and visualizations to develop and test an effective spam detection model.

## Project Overview

The primary steps involved in this project are:
1. **Data Collection**: Collected a labeled dataset of emails from Kaggle, including both spam and non-spam emails.
2. **Data Preprocessing**: Cleaned the text data by removing unnecessary characters, stopwords, and performed other preprocessing tasks to enhance model performance.
3. **Exploratory Data Analysis (EDA)**: Visualized data to gain insights into common patterns within spam and non-spam emails.
4. **Feature Engineering**: Used `CountVectorizer` to convert email content into a matrix of token counts, transforming categorical data into a format suitable for model training.
5. **Data Splitting**: Split data into training and testing sets, with 70% of the data used for training and 30% for testing.
6. **Model Selection and Training**: Tested various algorithms for spam classification. The `BinomialNB` algorithm demonstrated the highest accuracy among tested models.
7. **Model Evaluation**: Trained the model with `BinomialNB`, achieving an accuracy of 97% on the testing data.

## Installation

To run this project locally:
1. Clone the repository.
2. Install the necessary Python packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Load the dataset into the project.
2. Run the preprocessing and feature engineering steps to prepare the data.
3. Execute the model training script to train the `BinomialNB` classifier.
4. Evaluate the model using the testing data split.

## Results

The final model achieved a 97% accuracy, indicating high effectiveness in detecting spam emails.


This README outlines the essential details of your project for anyone interested in understanding or replicating it!
