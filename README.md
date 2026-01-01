📊 **Sentiment Analysis on Customer Feedback**
**📌 Project Overview**

This project performs Sentiment Analysis on customer feedback data using Python and Machine Learning.
The model classifies text reviews into Positive, Negative, or Neutral sentiments.
It also includes text preprocessing, visualization using WordCloud, and a custom prediction function for real-time sentiment analysis.

**🧠 Features**

Data loading and exploration from CSV files

Text cleaning and preprocessing (removal of noise, special characters, etc.)

Sentiment-based WordCloud visualization

Machine Learning model for sentiment classification

Saved and reused model & vectorizer (.pkl files)

Custom function to predict sentiment for new user input

**🛠️ Technologies Used**

Python

Pandas

Regular Expressions (re)

Scikit-learn

WordCloud

Matplotlib

Joblib

Jupyter Notebook

**📊 Dataset**

File: cutomer_feedback.csv

Key Columns:

text – Customer feedback

sentiment – Label (positive / negative / neutral)

⚙️ Installation & Setup

Clone the repository:

git clone https://github.com/your-username/sentiment-analysis.git


Navigate to the project folder:

cd sentiment-analysis


Install required libraries:

pip install pandas scikit-learn matplotlib wordcloud joblib


Open the notebook:

jupyter notebook SentimentAnalysis.ipynb

▶️ How It Works

Load customer feedback data

Clean and preprocess text

Visualize sentiments using WordCloud

Transform text using a trained vectorizer

Predict sentiment using a trained ML model

🔮 Sample Prediction
predict_sentiment("this product is really good")
# Output: positive

predict_sentiment("I hate this")
# Output: negative

predict_sentiment("This is okay")
# Output: neutral

📈 **Visualizations**

Separate WordClouds generated for:

Positive feedback

Negative feedback

Neutral feedback

These visuals help understand frequently used words in each sentiment category.

🚀 **Future Enhancements**
Deploy using Streamlit or Flask

Use Deep Learning models (LSTM / BERT)

Support multiple languages

Add real-time feedback input UI
