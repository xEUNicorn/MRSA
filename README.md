# Movie Review Sentiment Analysis (MRSA)
By: Chua, Ha, Misagal

This project performs sentiment analysis on movie reviews using various machine learning models, including TF-IDF, LSTM, and BERT. The dataset used is the IMDB Movie Reviews dataset.

## Project Structure

- `01_data_preparation.ipynb`: Data loading, preprocessing, and splitting.
- `02_tfidf_model.ipynb`: Implementation of TF-IDF based sentiment classification.
- `03_lstm_network.ipynb`: LSTM neural network for sentiment analysis.
- `04_bert_model.ipynb`: BERT model for advanced sentiment classification.
- `05_evaluation.ipynb`: Model evaluation and comparison.
- `data/`: Contains train, test, and validation CSV files.
- `IMDB Dataset.csv`: Raw IMDB dataset.

## Requirements

- Python 3.8+
- Jupyter Notebook
- Libraries: pandas, numpy, scikit-learn, tensorflow, transformers, torch, etc.

## Usage

Run the notebooks in order from 01 to 05 to reproduce the analysis.

1. Start with data preparation.
2. Train models.
3. Evaluate results.

## Dataset

The IMDB dataset contains 50,000 movie reviews labeled as positive or negative.
