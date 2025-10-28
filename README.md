# NLP-PROJECT---CHATBOT

🤖 Chatbot Projects – University FAQ & Customer Support

This repository contains two simple chatbot projects developed in Python — one for university FAQs and one for online shopping support.
Both use basic NLP (Natural Language Processing) techniques such as text preprocessing, TF-IDF, and intent recognition.

📘 Project 1: University FAQ Chatbot
🎯 Goal

Build a chatbot that answers student queries related to university information such as admissions, hostel, exams, fees, and timetable.

🔑 Concepts Used

Text preprocessing (tokenization, stopword removal, lemmatization)

TF-IDF for query matching

Cosine similarity to find the best matching question

Rule-based responses

🛠️ Tools & Libraries

Python

NLTK

Scikit-learn (TF-IDF + Cosine Similarity)

(Optional) Streamlit or Flask for web deployment

🧠 Example Dataset
Question	Answer
How much is the admission fee?	Admission fee is ₹5000.
How can I apply for a hostel?	Fill the hostel form online at hostel.university.edu.
When will exams start?	Exams will begin in December as per the academic calendar.
⚙️ Workflow

Preprocess the dataset (tokenize, remove stopwords, lemmatize)

Preprocess the user query

Convert text to TF-IDF vectors

Compute cosine similarity

Return the best matching answer

🚀 How to Run

Install dependencies:

pip install nltk scikit-learn pandas


Run the chatbot:

python university_chatbot.py


Chat example:

🎓 University FAQ Chatbot
Type 'exit' to quit.

You: How much is the admission fee?
Chatbot: Admission fee is ₹5000.

💡 Possible Extensions

Use BERT embeddings for better semantic understanding

Add multi-language support for international students

Deploy on Telegram, WhatsApp, or a web portal
