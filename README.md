# Fake News Detection using LSTM

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![LSTM](https://img.shields.io/badge/Model-LSTM-green)
![NLP](https://img.shields.io/badge/Field-Natural%20Language%20Processing-yellow)

A deep learning-based project to detect fake news using Long Short-Term Memory (LSTM) networks. This project aims to classify news articles as "Real" or "Fake" by analyzing their textual content.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Dataset](#dataset)
4. [Installation](#installation)
5. [Results](#results)

---

## Introduction
Fake news has become a significant issue in the digital age, spreading misinformation and influencing public opinion. This project leverages the power of **LSTM (Long Short-Term Memory)** networks, a type of Recurrent Neural Network (RNN), to detect fake news by analyzing the textual content of news articles.

The model is trained on a labeled dataset of news articles and can predict whether a given news article is "Real" or "Fake" with high accuracy.

---

## Features
- **Text Preprocessing**: Includes tokenization, stopword removal, and padding.
- **LSTM Model**: Utilizes LSTM layers for sequential text analysis.
- **Real-Time Prediction**: A web interface to input news text and get predictions.
- **Scalable**: Can be extended to larger datasets and more complex models.

---

## Dataset
The dataset used for this project is [Fake News Dataset](https://gitlab.com/atlonxp/siit-nlp/-/raw/main/dl-rnn/fake-new-dataset.zip?ref_type=heads&inline=false). It contains two CSV files:
- `True.csv`: Articles labeled as real news.
- `Fake.csv`: Articles labeled as fake news.

Each dataset contains the following columns:
- `title`: The title of the news article.
- `text`: The content of the news article.
- `subject`: The subject or category of the news.
- `date`: The publication date.

---

## Installation
To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/MoaazMahmoud22/Human-Face-Detection-with-LSTM.git]
   cd fake-news-detection

## Results
![image](https://github.com/user-attachments/assets/169efe51-fec0-42ce-b3af-b8a02a0df6fc)



