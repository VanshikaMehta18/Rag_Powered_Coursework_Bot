# Rag_Powered_Coursework_Bot
This repo contains a RAG-powered chatbot that answers subject-specific questions using content from PPTs. It processes the text through GPT-4o-mini and FAISS for accurate responses. Using HuggingFace embeddings and LangChain for efficient retrieval, it’s built with Flask, HTML, CSS, and JavaScript for an intuitive UI.

# Code Structure
The project is structured as follows:

rag.py: Implements the RAG-powered chatbot using Flask, GPT-4o-mini, FAISS, and HuggingFace embeddings. It processes text extracted from PPTs and retrieves relevant answers.
index.html: Provides a simple front-end with HTML, CSS, and JavaScript for user interaction with the chatbot.

# How to Prepare to Run
Prerequisites
Install Python 3.7 or higher.
Set up an OpenAI API key in the .env file.

Install required dependencies:
pip install -r requirements.txt
# How to Run
Clone the repository:
git clone https://github.com/your-repo-name.git
cd your-repo-name
Install dependencies as mentioned above.
# Run the Flask application:
python rag.py
Open http://127.0.0.1:5000/ in your browser to access the chatbot.

# What the Code Does
Extracts text from PPT files(In this project, I have used the DBMS(database management system course) and splits it into chunks for efficient retrieval.
Embeds and stores data using FAISS and HuggingFace embeddings.
Retrieves relevant answers using a retrieval-augmented generation (RAG) approach.
Handles user queries via a Flask API, integrating with a front-end built using HTML, CSS, and JavaScript.


