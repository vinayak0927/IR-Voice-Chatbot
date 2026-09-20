# IR Voice Chatbot

An Information Retrieval based voice chatbot developed using Python and Google Colab.

The chatbot accepts a user's question, searches a predefined knowledge base using TF-IDF and Cosine Similarity, retrieves the most relevant answer, and converts the answer into speech.

## Features
- Information Retrieval based chatbot
- TF-IDF vectorization
- Cosine Similarity
- Question-answer matching
- Text-to-Speech response
- Google Colab compatible
- Customizable knowledge base

##  Working

User Question
↓
Text Preprocessing
↓
TF-IDF Vectorization
↓
Cosine Similarity
↓
Find Most Relevant Question
↓
Retrieve Answer
↓
Text-to-Speech
↓
Voice Response

## Technologies

- Python
- Google Colab
- Scikit-learn
- TF-IDF
- Cosine Similarity
- gTTS
- IPython

## How to Run

Open the `.ipynb` file using Google Colab and execute the cells sequentially.

Install the required libraries:

```bash
pip install scikit-learn gTTS
