# Introduction to Text Classification with NLP

This project demonstrates a basic **Text Classification** workflow using **Natural Language Processing (NLP)**. The goal is to classify text messages into two categories: **spam** and **ham**. The classification is done using **Logistic Regression**, a popular machine learning model.

## Project Workflow:

1. **Text Preprocessing**:  
   - Tokenization  
   - Removal of stopwords  
   - Lowercasing and normalization of text data

2. **Feature Extraction**:  
   - **TF-IDF** (Term Frequency-Inverse Document Frequency) to convert the text into numerical data that can be used by the machine learning model.

3. **Model Training**:  
   - **Logistic Regression** is used to train a binary classification model to classify the text as **spam** or **ham**.

4. **Model Evaluation**:  
   - The performance of the model is evaluated using accuracy and a classification report, including precision, recall, and F1-score.

## Installation:

To run the code in this repository, you need to install the following dependencies:

```bash
pip install -r requirements.txt
```

Requirements:
Python 3.x
scikit-learn
nltk
pandas
Instructions:
Clone this repository.
Run the Jupyter notebook to see the full code and explanations.
Use the provided functions to preprocess the data, train the model, and evaluate its performance.
