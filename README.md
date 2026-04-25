📩 Spam Message Detection using NLP & Average Word2Vec
📌 Overview

This project is a Spam Message Classifier built using Natural Language Processing (NLP) and Machine Learning.
The model analyzes text messages and predicts whether a message is Spam or Ham (Not Spam).

The project uses Word2Vec embeddings and Average Word2Vec for converting text into meaningful numerical vectors before feeding them into a machine learning model.

🚀 Features

✅ Text preprocessing and cleaning
✅ Tokenization of messages
✅ Stopword removal
✅ Word embedding using Word2Vec
✅ Document embedding using Average Word2Vec
✅ Spam / Ham classification
✅ Model evaluation with accuracy score
✅ Handles missing vocabulary vectors safely

🛠 Tech Stack
Python
NumPy
Pandas
NLTK
Gensim
scikit-learn
Jupyter Notebook
📂 Project Workflow
Load dataset
Clean text data
Tokenize messages into words
Train / use Word2Vec model
Convert each message into vector using Average Word2Vec
Train Machine Learning classifier
Evaluate performance
Predict Spam / Ham for new messages
🧠 Average Word2Vec Formula

Average of all word vectors in a document:

\bar{v}=\frac{1}{n}\sum_{i=1}^{n} v_i

Where:

n = number of words
vᵢ = word embedding vector
v̄ = final document vector
📊 Model Performance

Accuracy: XX% (update with your result)

Example:

Prediction: Spam
Confidence: High
💡 Challenges Solved

During development:

Fixed NaN vector issue when document had no valid vocabulary
Solved dimension mismatch error while converting embeddings into arrays
Improved preprocessing pipeline for better vector quality
🔮 Future Improvements
Implement TF-IDF weighted Word2Vec
Try LSTM / GRU / BERT
Deploy as a web app using Streamlit / Flask
Add real-time SMS classification API
👨‍💻 Author

Sumit Kumar
B.Tech Information Technology (2026)
Aspiring AI / ML Engineer | Data Analyst | NLP Enthusiast

Connect on LinkedIn : https://www.linkedin.com/in/sumit-kumar-1b6207388/
