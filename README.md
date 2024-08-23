# Credit Card Fraud Detection

This project aims to detect fraudulent transactions from credit card data using various machine learning models. The dataset consists of 100,000 credit card transactions, including features such as transaction type, card type, country, amount, and whether the transaction was fraudulent.

## Project Overview

The goal of this project is to build a machine learning model that can accurately classify whether a transaction is fraudulent or not. The project covers the following steps:

1. Data Acquisition and Exploration
2. Data Preprocessing
3. Model Building and Evaluation
4. Final Predictions and Analysis

## Dataset

The dataset used in this project includes the following features:

- **Transaction ID**: Unique identifier for the transaction
- **Date**: Date of the transaction
- **Day of Week**: Day of the week of the transaction
- **Time**: Time of the transaction
- **Type of Card**: Type of credit card used
- **Entry Mode**: Mode of transaction entry (e.g., PIN, Swipe, etc.)
- **Amount**: Transaction amount
- **Type of Transaction**: Type of transaction (e.g., POS, Online, ATM)
- **Merchant Group**: Category of the merchant where the transaction occurred
- **Country of Transaction**: Country where the transaction took place
- **Shipping Address**: Shipping address for the transaction
- **Country of Residence**: Country of residence of the cardholder
- **Gender**: Gender of the cardholder
- **Age**: Age of the cardholder
- **Bank**: Bank that issued the card
- **Fraud**: Target variable indicating whether the transaction was fraudulent (1) or not (0)

## Project Structure

- **`frauddetection.ipynb`**: Jupyter notebook containing all the code for data exploration, preprocessing, model building, and evaluation.
- **`CreditCardDataset.csv`**: Dataset used in this project (not included in the repository).
- **`README.md`**: Overview of the project (this file).
