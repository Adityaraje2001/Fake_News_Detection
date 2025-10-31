📰 Fake News Detection using NLP and LSTM-RNN
🔍 Overview

This project aims to detect fake news articles using Natural Language Processing (NLP) and a Long Short-Term Memory (LSTM) Recurrent Neural Network.
The model learns textual patterns and linguistic cues to classify news as Fake (0) or Real (1) based on their content.

🚀 Features

Preprocessing of raw news text (cleaning, tokenization, stopword removal, padding)

Word embeddings using Keras Embedding Layer

Deep learning model using LSTM (RNN variant)

Binary classification output (Fake vs Real)

Model evaluation using accuracy, confusion matrix, and classification report

Easy testing for custom news samples

🧠 Tech Stack
Category	Tools & Libraries
Language	Python
Libraries	TensorFlow / Keras, NumPy, Pandas, Matplotlib, scikit-learn
NLP	NLTK / re (for preprocessing)
Model	LSTM (Recurrent Neural Network)
📂 Dataset

You can use any labeled fake news dataset such as:

Kaggle: Fake News Dataset

(Columns: id, title, author, text, label — where label = 0 → Fake, 1 → Real)
