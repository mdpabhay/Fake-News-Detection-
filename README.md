# 📰 Fake News Detection Web Application

This project is a **Python-based web application** designed to identify and rate the credibility of news articles as either "Real" or "Fake" using **Machine Learning** and **Natural Language Processing (NLP)**. Built with **Logistic Regression**, this application achieves **90% accuracy** in detecting fake news, providing a quick and intuitive way for users to assess news authenticity. Developed with Flask, the app processes text data in real time.

---

## 📖 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Workflow](#model-workflow)
- [Performance Metrics](#performance-metrics)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## 📌 Project Overview

The **Fake News Detection Web Application** addresses the growing need to detect misinformation. Leveraging Logistic Regression with NLP, the app classifies news articles and generates a credibility score for each. With a focus on user experience, the app allows users to upload or paste article text, view results, and make informed judgments quickly.

---

## ✨ Features

- **High Accuracy**: Reaches 90% accuracy in classification.
- **Real-Time Analysis**: Processes articles in under 1 second.
- **Credibility Score**: Rates the likelihood of news authenticity.
- **User-Friendly Interface**: Simple, accessible design using Flask.

---

## 🔧 Technologies Used

- **Programming Language**: Python
- **Framework**: Flask
- **Machine Learning**: Logistic Regression, Scikit-Learn
- **Natural Language Processing**: TF-IDF, NLTK
- **Data Handling**: Pandas, NumPy
- **Performance Metrics**: F1 Score, Precision, Recall, Accuracy


## 📊 Performance Metrics

- The Logistic Regression model is optimized for accuracy and speed, providing dependable results with minimal delay.

- Accuracy: 90% on test data
- Precision: Minimizes false positives
- F1 Score: Balances precision and recall effectively
- Why Logistic Regression?
- Logistic Regression is ideal for binary classification and handles textual data effectively, making it well-suited for this project.
---

## 🚀 Installation

To set up this project locally, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/fake-news-detection.git
   cd fakenewsdetection




# **Project Structure**
- fake-news-detection/ │
- ├── app.py # Main application file
- ├── requirements.txt # Project dependencies
- ├── models/ # Contains ML model files
- ├── templates/ # HTML templates for Flask
- ├── static/ # Static files (CSS, JS, images)
- ├── data/ # Dataset and preprocessed files
- └── README.md # Project documentation





# **WorkFlow**

                +--------------------------+
                |                          |
                |   Start: Load Interface  |
                |                          |
                +-------------+------------+
                              |
                              v
                +-------------+------------+
                |                          |
                | Input Article (Text)     |
                |                          |
                +-------------+------------+
                              |
                              v
                +-------------+------------+
                |                          |
                | Preprocess Text Data     |
                | (Tokenization, TF-IDF)   |
                +-------------+------------+
                              |
                              v
                +-------------+------------+
                |                          |
                | Run ML Model             |
                | (Logistic Regression)    |
                +-------------+------------+
                              |
                              v
                +-------------+------------+
                |                          |
                | Generate Output          |
                | - Classification         |
                | - Credibility Score      |
                +-------------+------------+
                              |
                              v
                +-------------+------------+
                |                          |
                | Display Results          |
                |                          |
                +--------------------------+

