# Fake News Detection using PassiveAggressiveClassifier

This project demonstrates a basic machine learning model for detecting fake news using a PassiveAggressiveClassifier. The dataset used is a collection of news articles, and the goal is to classify them as either real or fake.

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)

## Overview

Fake news has become a major issue in today's digital world. This project provides a simple yet effective way to classify news articles as real or fake using Natural Language Processing (NLP) techniques and a machine learning model. The PassiveAggressiveClassifier is particularly suited for large-scale text classification tasks where the model is updated continuously with new data.

## Installation

To run this project, you will need to have Python installed on your machine. Additionally, you need to install the required Python packages.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/your-repository.git
   cd your-repository

2. **Install the required packages:**
   ```bash
   pip install numpy pandas scikit-learn

## Dataset

The dataset used in this project is a collection of news articles stored in a CSV file. Each article is labeled as either "FAKE" or "REAL". The dataset is loaded using Pandas, and the text data is processed using TF-IDF vectorization.

The CSV file should be placed in the path: C:\yourpath\

## Usage

1. Prepare the Dataset:

Load the dataset and split it into training and testing sets.
Initialize a TfidfVectorizer to transform the text data into numerical features.

2. Train the Model:

Initialize the PassiveAggressiveClassifier and train it on the TF-IDF features extracted from the training set.

3. Evaluate the Model:

Predict the labels for the test set and calculate the accuracy.
Build a confusion matrix to understand the model's performance.


