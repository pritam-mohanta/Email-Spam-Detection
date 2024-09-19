# Email Spam Detection

This project aims to detect whether an email is **spam** or **not spam** using a machine learning model. The process includes data exploration, text preprocessing, model training, and building a web app for user interaction.

## Project Overview

1. **Dataset**: We first take a dataset containing labeled email data (ham or spam) and perform Exploratory Data Analysis (EDA) to understand its structure.
   
2. **Mapping Labels**: 
   - **Ham (Not Spam)** is mapped to `0`
   - **Spam** is mapped to `1`

3. **Text Preprocessing**: 
   - We use **CountVectorizer**, a technique commonly used in natural language processing (NLP) tasks. It converts a collection of text documents into a numerical representation (vectorization).

4. **Model Building**:
   - We split the dataset into training and testing data.
   - We use the **Naive Bayes Classifier** to train the model.

5. **Model Testing**: After training, we test the model’s performance on the test data.

6. **Web Application**: Finally, we built a web app using **Streamlit** to allow users to input an email and get predictions on whether it's spam or not.

## Tools & Libraries Used

- **Numpy**: For numerical operations
- **Pandas**: For data manipulation and analysis
- **Pickle**: For saving and loading the trained model
- **Scikit-learn (sklearn)**:
  - **CountVectorizer**: For text vectorization
  - **train_test_split**: To split the dataset
  - **Naive Bayes Classifier**: The machine learning algorithm used for classification
- **Streamlit**: For building the web application

## Methodology

1. **Dataset Preparation**: Load and explore the email dataset.
2. **Label Mapping**: Map the labels (`ham=0`, `spam=1`) to make the classification binary.
3. **Text Vectorization**: Convert the email text into numerical data using **CountVectorizer**.
4. **Model Training**: Split the dataset into training and testing sets, and apply the **Naive Bayes Classifier**.
5. **Testing**: Test the model’s accuracy and fine-tune as necessary.
6. **Web App**: Build a user-friendly web application using **Streamlit** to interact with the model.


