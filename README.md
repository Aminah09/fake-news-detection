# Real Time Fake News Detection using Data Science

## Description

The Fake News Detection project aims to detect and classify news articles as either fake or not fake (legitimate) using data science techniques. It utilizes machine learning algorithms and natural language processing (NLP) to analyze the textual content of news articles and make predictions based on the learned patterns.

## Dataset

The project employs the [Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset) available on Kaggle. The dataset contains labeled news articles, where fake news articles are labeled as 0 and legitimate news articles are labeled as 1.

## Implementation

The project involves the following steps:

1. Data Preprocessing: Clean the text data by removing unnecessary characters, stopwords, and performing tokenization and stemming/lemmatization.

2. Feature Extraction: Convert the preprocessed text data into numerical features using techniques like TF-IDF (Term Frequency-Inverse Document Frequency).

3. Model Training: Train a machine learning model, such as Logistic Regression, using the extracted features and the labeled dataset.

4. Model Evaluation: Evaluate the trained model's performance by calculating metrics like accuracy, precision, recall, and F1-score.

5. Model Testing: Use the trained model to predict the label (fake or not fake) for new/unseen news articles.

## Usage

1. Download or clone this repository to your local machine.

2. Install the required dependencies, including scikit-learn and numpy.

3. Download the Fake and Real News Dataset from [Kaggle](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset) and place it in the appropriate directory.

4. Run the code in a Python environment, such as Jupyter Notebook or any Python IDE.

5. Follow the instructions within the code to preprocess the data, train the model, and perform predictions.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to explore and modify the code according to your needs. Enjoy using the Fake News Detection using Data Science!


