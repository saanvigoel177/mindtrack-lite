# mindtrack-lite
Stress detection prototype using TensorFlow and Jupyter Notebook

📝 Introduction
MindTrack Lite is a lightweight, AI-powered tool designed to help detect early signs of academic stress and burnout in students based on short journal entries. By analyzing the sentiment behind a student’s words, it provides feedback on whether the entry reflects possible stress or a neutral/positive state of mind. The prototype simulates how an AI assistant could offer mental health support in educational settings.

💻 Tech Stack
Python (Jupyter Notebook) – for the core logic and interface
TensorFlow & TensorFlow Hub – for embedding and natural language processing (NLP)
IPyWidgets – for building a basic interactive user interface inside the notebook
Jupyter Notebook – as the platform for running and displaying the app

🌟 Features
✅ Simple text box where students can write their journal entry
✅ AI-based sentiment similarity check against a reference "stressed" statement
✅ Instant feedback: shows whether the student is likely stressed or not
✅ Runs entirely in Jupyter Notebook — no need for external hosting or UI frameworks
✅ No dataset or training required — uses pre-trained model

🔧 Google Technology Used
✅ TensorFlow Hub
Used Google’s Universal Sentence Encoder from TensorFlow Hub to convert natural language journal entries into vector embeddings.
Compared these embeddings with a reference stress-indicative phrase to determine emotional similarity.
This allowed stress detection without needing any labeled dataset or custom model training.
Model used: https://tfhub.dev/google/universal-sentence-encoder/4
