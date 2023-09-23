# Spam-Detection-Classifier

# SMS Spam Detection Project 📱🚫

## Table of Contents

- [About the Project](#about-the-project)
- [Demo](#demo)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Data](#data)
- [Preprocessing](#preprocessing)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Usage](#usage)

## About the Project

📚 This project is an SMS Spam Detection application that uses machine learning to classify text messages as spam or non-spam (ham). It can be used to filter out unwanted text messages, such as spam advertisements or phishing attempts.

🚀 Features:
- Text preprocessing to clean and tokenize messages.
- Classification using the Multinomial Naive Bayes algorithm.
- Evaluation metrics including accuracy, precision, recall, and F1-score.
- Easy-to-use interface for testing with custom messages.

## Getting Started

### Prerequisites

- Python (3.x recommended)
- Dependencies (listed in requirements.txt)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/yourusername/sms-spam-detection.git

## Data

The SMS Spam Detection project uses a dataset containing labeled examples of spam and non-spam text messages. You can find the dataset in the data directory of this repository. The dataset includes two main columns:

text: This column contains the text of the SMS messages.
label: This column specifies whether the SMS is spam (spam) or non-spam (ham).
You can use this dataset for training and evaluating the SMS Spam Detection model. To explore or modify the dataset, you can refer to the CSV files in the archive zip.

## Preprocessing
🧹 The text data is preprocessed using natural language processing techniques, including:

Lowercasing
Punctuation removal
Tokenization
Stopword removal
Stemming
T
## Training
🤖 The model is trained using the Multinomial Naive Bayes algorithm. The training process includes vectorizing the text data and fitting the classifier to the training set.

## Evaluation
📈 Model performance is evaluated using various metrics, such as accuracy, precision, recall, and F1-score. The evaluation results are displayed in the README.

## Results
📊 Here are the results of the SMS Spam Detection model on a test dataset:

Accuracy: 98.03%
Precision (spam): 0.97
Recall (spam): 0.88
F1-score (spam): 0.92

## Usage
You can use this SMS Spam Detection application to classify text messages as spam or non-spam (ham). Follow these steps to use the application:

Step 1: Clone the repository to your local machine:
```sh
git clone https://github.com/yourusername/sms-spam-detection.git

Step 2: Navigate to the project directory:
```sh
cd sms-spam-detection

Step 3: Install the required dependencies by running:
```sh
pip install -r requirements.txt
