# Financial Text Sentiment Analysis

## Introduction
Welcome to the Sentiment Analysis project! This project focuses on analyzing sentiment from text data, categorizing it into positive, negative, or neutral sentiments. By following a systematic process involving Exploratory Data Analysis (EDA), preprocessing, bag-of-words representation, and utilizing multiple machine learning models, this project aims to extract insights from textual content and understand the sentiment expressed within it.

## Process Overview
### 1. Exploratory Data Analysis (EDA)
- **Data Exploration**: Understand the distribution of sentiment labels in the dataset.

### 2. Preprocessing
- **Text Cleaning**: Remove noise, special characters, and irrelevant symbols from the text.
- **Tokenization**: Split text into individual tokens (words or n-grams).
- **Lowercasing**: Convert text to lowercase for consistency.
- **Stopword Removal**: Eliminate common stopwords.
- **Stemming/Lemmatization**: Normalize words to their root form.
- **Feature Engineering**: Create additional features such as word counts or TF-IDF scores.

### 3. Bag of Words Representation
- **Vectorization**: Transform preprocessed text data into numerical vectors.
- **Feature Extraction**: Extract features from text data while preserving frequency information.
- **Vocabulary Construction**: Build a vocabulary of unique words or n-grams.

### 4. Multiple Machine Learning Models
- **Model Selection**: Choose from various machine learning algorithms.
- **Model Training**: Train each selected model on preprocessed and vectorized data.
- **Hyperparameter Tuning**: Optimize model hyperparameters.
- **Model Evaluation**: Evaluate performance using metrics like accuracy, precision, recall, F1-score, or ROC-AUC.

### 5. Evaluation
- **Evaluation Metrics**: Calculate various evaluation metrics to gauge model performance.
- **Confusion Matrix**: Analyze model predictions and misclassifications.

## Usage
To use this sentiment analysis pipeline:
1. Clone the repository: `git clone https://github.com/Avyukth1C/financial-text-sentiment.git`
2.Unzip the files.
3. Import the .ipynb into Google Colab.
4. Import the dataset into your Google drive.[Change the file path in the code respectively]
5. Run the Jupyter notebook provided in the repository to Train the machine learning models using the prepared dataset.
6. Use the functions for real-time sentiment analysis.

## Support
If you encounter any issues or have questions about the Sentiment Analysis project, please feel free to create an issue in the repository.[create an issue](https://github.com/Avyukth1C/financial-text-sentiment/issues).


## License
This project is licensed under the MIT License.[MIT License](LICENSE).
