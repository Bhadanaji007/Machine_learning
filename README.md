# Fake News Detection Project

This project aims to detect fake news using machine learning techniques. It utilizes a dataset of news articles and employs a Logistic Regression model to classify news as either fake or real.

## Dataset

The dataset used in this project is the "fake_or_real_news.csv" file. It contains news articles labeled as either "FAKE" or "REAL".

## Methodology

1. **Data Preprocessing:** The dataset is cleaned and preprocessed by removing irrelevant characters, converting text to lowercase, removing stop words, and applying stemming.
2. **Feature Extraction:** TF-IDF (Term Frequency-Inverse Document Frequency) is used to extract features from the text data.
3. **Model Training:** A Logistic Regression model is trained on the preprocessed data.
4. **Model Evaluation:** The model's performance is evaluated using accuracy score on both training and testing data.

## Usage

1. **Install Dependencies:** Make sure you have the necessary libraries installed. You can install them using `pip install -r requirements.txt`.
2. **Run the Notebook:** Open the "fake_news_detection.ipynb" notebook in Google Colab and run the cells to execute the code.
3. **Input Data:** You can input new news articles to the model for prediction.

## Results

The model achieved an accuracy of approximately 92% on the training data and 91% on the testing data.

## Contributing

Contributions to this project are welcome. Please feel free to submit pull requests or open issues.


