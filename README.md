PDF Question Answering Bot

A Python-based PDF Question Answering (QA) application that allows users to upload a PDF document and ask questions about its contents through an interactive Gradio web interface.

Project Overview

This project demonstrates how a Retrieval-Augmented Generation (RAG) style application can be used to interact with information contained in PDF documents.

Users can:

Upload a PDF document

Enter a question about the document

Process the document using the application's retrieval and question-answering pipeline

Receive an answer through a simple web-based interface

Features

📄 PDF document upload

🔎 Question answering based on uploaded documents

🤖 AI-powered response generation

🖥️ Interactive Gradio user interface

🐍 Python-based implementation

🔐 Environment variables used for sensitive configuration

Technologies Used

Python

Gradio — interactive web interface

FastAPI / Starlette — web application infrastructure

Jinja2

AI / NLP components

PDF document processing

Git & GitHub

Project Structure
qa-bot/
├── app.py
├── qabot.py
├── documents/
├── .gitignore
└── README.md

How It Works

The user uploads a PDF document.

The application processes the document.

The user enters a question related to the document.

The question-answering pipeline retrieves relevant information.

The application generates and displays an answer.

Installation

Clone the repository:

git clone https://github.com/Ravi-Pandya506/pdf-question-answering-bot.git
cd pdf-question-answering-bot


Create and activate a virtual environment:

python3.11 -m venv my_env
source my_env/bin/activate


Install the required dependencies:

pip install -r requirements.txt

Running the Application

Start the application with:

python qabot.py


The Gradio application will then be available through the URL displayed in the terminal.

Security

Sensitive credentials and environment variables should not be committed to GitHub.

The .env file is excluded through .gitignore.

Project Purpose

This project was developed to demonstrate practical skills in:

Python application development

Generative AI

Natural Language Processing

Retrieval-Augmented Question Answering

Document processing

Gradio application development

Git and GitHub

Author

Ravi Pandya

GitHub: Ravi-Pandya506
