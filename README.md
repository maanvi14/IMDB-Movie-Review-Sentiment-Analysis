🎬 Sentiment Analysis on IMDB Movie Reviews
📌 Project Overview
This project focuses on performing Sentiment Analysis on the popular IMDB Movie Review Dataset using both traditional Machine Learning (Multinomial Naive Bayes) and Deep Learning (Simple RNN) approaches.
The project also features a Streamlit web application for live text sentiment prediction.

🗂️ Dataset
IMDB Movie Reviews Dataset
Contains 50,000 movie reviews labeled as positive or negative.
Dataset is balanced and commonly used for binary text classification tasks.
🚀 Technologies Used
Python 3.x
Scikit-learn (Multinomial Naive Bayes Classifier)
TensorFlow / Keras (Simple RNN)
Streamlit (Web App Deployment)
NumPy, Pandas, Matplotlib/Seaborn (for EDA & Visualization)
📊 Model Performance
Model	Accuracy
Multinomial Naive Bayes	87%
Simple RNN	92%
📈 Sample Classification Report (Naive Bayes):
(See classification report image in repo)

📚 Learnings
ML vs DL for NLP: Why sequential models (RNNs) outperform BOW/TF-IDF for context-rich data.
Effect of word embeddings and sequences on classification performance.
Model evaluation using precision, recall, F1-score.
Deploying models using Streamlit for quick app prototyping.
🔍 Real-World Use Cases
Movie Review Analysis on streaming platforms.
Product Sentiment Analysis in E-commerce.
Customer Feedback Systems.
Brand Sentiment Tracking on social media.
Financial Market Mood Detection based on news/tweets.

## ✅ Future Work
- Implement **LSTM/GRU models** for improved sequential data handling.
- Support for **multilingual sentiment analysis**.
- **Web dashboard** for real-time sentiment visualization.
