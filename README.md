📄 PDF Question Answering Bot

An AI-powered Python application that allows users to upload a PDF document and ask questions about its content through an interactive web interface.






🎯 Project Overview

The PDF Question Answering Bot is a beginner-friendly AI/NLP project that demonstrates how users can interact with information contained in PDF documents using a question-answering pipeline.

The application provides a simple Gradio web interface where users can upload a PDF, enter a question, and receive an AI-generated answer based on the document.

This project was developed as part of my practical learning in Generative AI, Natural Language Processing, Python, and Git/GitHub.

✨ Features

📄 Upload PDF documents

🔎 Ask questions about uploaded documents

🤖 Generate AI-powered answers

🖥️ Interactive Gradio web interface

🐍 Python-based implementation

🔐 Environment variables for sensitive configuration

📚 Document-based question answering

🚀 Simple local application deployment

🛠️ Technologies Used
Technology	Purpose
🐍 Python	Application development
🤗 Gradio	Interactive web interface
⚡ FastAPI	Web application infrastructure
⭐ Starlette	ASGI framework infrastructure
🎨 Jinja2	Template support
🤖 AI / NLP	Question answering
📄 PDF Processing	Document processing
🔧 Git	Version control
🐙 GitHub	Source code management
🔄 How It Works
        📄 PDF Document
               │
               ▼
      ┌──────────────────┐
      │ Document          │
      │ Processing        │
      └────────┬─────────┘
               │
               ▼
      ┌──────────────────┐
      │ Question from    │
      │ User             │
      └────────┬─────────┘
               │
               ▼
      ┌──────────────────┐
      │ Retrieval /      │
      │ QA Pipeline      │
      └────────┬─────────┘
               │
               ▼
      ┌──────────────────┐
      │ AI Generated     │
      │ Answer           │
      └──────────────────┘

User Flow

Upload a readable PDF document.

Enter a question related to the document.

The application processes the document.

Relevant information is retrieved.

The question-answering pipeline generates a response.

The answer is displayed in the Gradio interface.

📸 Application Screenshot

The application provides a simple interface for uploading a PDF and asking questions.

Screenshot will be added here.

<!-- When you upload your screenshot to GitHub, replace the line above with: ![PDF Question Answering Bot](screenshots/QA_bot.png) -->
📁 Project Structure
pdf-question-answering-bot/
│
├── 📄 app.py
├── 📄 qabot.py
├── 📄 requirements.txt
├── 📄 README.md
├── 📄 .gitignore
│
├── 📂 documents/
    └── 🖼️ QA_bot.png

⚙️ Installation
1. Clone the repository
git clone https://github.com/Ravi-Pandya506/pdf-question-answering-bot.git
cd pdf-question-answering-bot

2. Create a virtual environment
python3.11 -m venv my_env

3. Activate the virtual environment
source my_env/bin/activate

4. Install dependencies
pip install -r requirements.txt

▶️ Running the Application

Start the application with:

python qabot.py


The Gradio application will then be available through the URL displayed in the terminal.

🔐 Security

Sensitive credentials and API keys should never be committed to GitHub.

This project uses environment variables for sensitive configuration, and the .env file is excluded using .gitignore.

.env
my_env/
__pycache__/
*.pyc
flagged/

🎓 What I Learned

Through this project, I gained practical experience with:

🐍 Python application development

🤖 Generative AI concepts

🧠 Natural Language Processing

🔎 Retrieval-Augmented Question Answering concepts

📄 PDF document processing

🖥️ Gradio application development

🌐 Running a local web application

🔐 Managing environment variables

🔧 Git version control

🐙 GitHub repository management

🚀 Future Improvements

Some possible improvements for future versions include:

Support for multiple PDF documents

Conversation history

Improved document retrieval

Better handling of large documents

More advanced UI design

Source/reference display for generated answers

Deployment as a public web application

👨‍💻 About Me

Ravi Pandya

Aspiring AI / Python Developer interested in:

Artificial Intelligence

Generative AI

Natural Language Processing

Python Development

Machine Learning

Building practical AI applications

🔗 GitHub

Ravi-Pandya506

⭐ If you find this project useful, feel free to explore the repository and learn from the implementation.
