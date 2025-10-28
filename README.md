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

🛍️ Project 2: Customer Support Chatbot for Online Shopping
🎯 Goal

Create a chatbot that handles customer queries like order tracking, returns, delivery info, and product details.

🔑 Concepts Used

Intent recognition (keyword-based)

Named Entity Recognition (regex for order numbers)

Text preprocessing (tokenization, lemmatization, stopword removal)

Rule-based responses

🛠️ Tools & Libraries

Python

NLTK

re (Regular Expressions)

(Optional) Streamlit or Flask for deployment

🧠 Example Queries
User Query	Chatbot Response
Where is my order #12345?	Your order #12345 is out for delivery. 📦
How can I return a product?	You can return products within 15 days via our online portal.
How long does delivery take?	Standard delivery takes 3–5 business days.
⚙️ Workflow

Preprocess the user input

Detect intent using keyword matching

Extract order number using regex

Generate and return the appropriate response

🚀 How to Run

Install dependencies:

pip install nltk


Run the chatbot:

python customer_chatbot.py


Chat example:

🛍️ Customer Support Chatbot
Type 'exit' to quit.

You: Where is my order #12345?
Chatbot: Your order #12345 is out for delivery. 📦

💡 Possible Extensions

Add ML-based intent classification

Include real-time database or API integration

Perform sentiment analysis to detect frustrated customers

Deploy on web or messaging platforms

🧰 Project Folder Structure
📁 chatbot-projects
│
├── 📘 university_chatbot.py         # Project 1 code
├── 🛍️ customer_chatbot.py           # Project 2 code
├── README.md                        # Documentation (this file)
└── requirements.txt                 # Python dependencies (optional)

🧑‍💻 Author

[Your Name]
🎓 University Project – Chatbot Development
📧 your.email@example.com
