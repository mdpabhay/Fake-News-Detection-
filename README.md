# Fake-News-Detection-
A Python-based app using Logistic Regression and NLP to detect fake news with 90% accuracy. Provides instant credibility ratings and real-time processing for swift, reliable results. Built with Flask for a seamless user experience in tackling misinformation.

This Python-based web application detects fake news articles and provides a credibility rating using Machine Learning and Natural Language Processing (NLP). Developed with Logistic Regression and Flask, the model achieves an accuracy of over 90%.

**Table of Contents**        
Introduction          
Features                          
Technologies Used              
Setup and Installation              
Usage            
Model Performance              
Project Structure              
Contributing                
License              


**Introduction**
Fake news has become a significant problem, spreading misinformation and misleading readers. This project addresses this issue by using a machine learning model to classify articles as either "Real" or "Fake" and provides a credibility rating for each article.

**Features**
High Accuracy: Logistic Regression model with over 90% accuracy in detecting fake news.

Real-Time Analysis: Processes and rates each article in under 1 second.

Credibility Score: Provides a rating for each article, indicating the likelihood of it being real or fake.

User-Friendly Interface: Built with Flask for easy article uploads and instant feedback.

Technologies Used

Programming Language: Python

Machine Learning: Logistic Regression, Scikit-Learn

Natural Language Processing: Tokenization, TF-IDF (Term Frequency-Inverse Document Frequency)

Web Framework: Flask

Libraries: Pandas, NumPy, Scikit-Learn, NLTK

Setup and Installation

Clone the Repository



bash

Copy code

git clone https://github.com/your-username/fake-news-detection.git

cd fake-news-detection

Create a Virtual Environment



bash

Copy code

python3 -m venv venv

source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

Install Dependencies



bash

Copy code

pip install -r requirements.txt

Download Pre-trained Model (If Available)


Place any pre-trained model files in the models/ directory.

Run the Application



bash

Copy code

python app.py

Open your browser and go to http://127.0.0.1:5000 to access the application.

Usage

Upload an Article: Paste or upload an article you want to verify.

Analyze: Click "Analyze" to check if the article is likely fake or real.

View Results: Get a credibility score and classification label (Real or Fake) based on the model’s analysis.

Model Performance

Accuracy: 90% on test data

False Positive Reduction: Improved precision by 15% to minimize misclassification

Real-Time Processing: Average processing time of <1 second per article





**Project Structure**



fake-news-detection/          

│                

├── app.py                        # Main application file    






├── requirements.txt              # Dependencies        





├── models/                       # Directory for ML models    




├── templates/                    # HTML templates for Flask   





├── static/                       # CSS, JS, and other static files   





├── data/                         # Dataset and preprocessed files     





└── README.md                     # Project README file          








Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes or suggestions.



Fork the Repository

Create a New Branch

Commit Your Changes

Push the Branch and Open a Pull Request

License

This project is licensed under the MIT License. See the LICENSE file for details.



Feel free to customize this README further to include any specific datasets, pretrained models, or configuration steps that apply to your project. This format ensures 
clarity, easy setup for other developers, and comprehensive documentation.











