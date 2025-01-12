# Sentiment Analysis Project

This project is a sentiment analysis tool that uses machine learning models to classify the sentiment of text data as either positive or negative. The project includes both traditional machine learning and deep learning approaches.

## Overview
This project aims to analyze the sentiment of tweets. It leverages both Logistic Regression and a simple Deep Learning model to predict the sentiment of a given text. The dataset used is preprocessed and stored in a pickle file.


## Project Structure
- **notebooks/**: Contains Jupyter notebooks used for exploration and development.
- **pickles/**: Contains pickle files for models and data.
- **deployment/**: Contains deployment scripts and files.
- **requirements.txt**: Lists all dependencies required for the project.
- **README.md**: This file.
- **cleaned_tweets.pkl**: Preprocessed dataset.
- **LR_Pipeline.pickle**: Saved Logistic Regression model pipeline.
- **tokenizer.pickle**: Saved tokenizer used in the deep learning model.

## Models
- **Logistic Regression**: Uses a Count Vectorizer and Logistic Regression with cross-validation.
- **Deep Learning Model**: Uses a Sequential model with Dense layers and binary cross-entropy loss function.

## Evaluation
The models are evaluated using accuracy as the primary metric. Cross-validation is used for Logistic Regression, and a validation split is used for the Deep Learning model. The best model is saved during training based on validation loss.

## Dependencies
- numpy
- pandas
- scikit-learn
- keras
- tensorflow
- matplotlib

Install dependencies using:
```sh
pip install -r requirements.txt
```
