# AskPDF
AskPDF is one of the many applications of LLM use-cases. It allows extensive interactions with PDF files by answering the questions that users input about the uploaded PDF file.

Aside from basic prompting and LLMs, text-splitting and retrieval are essential components of AskPDF. Since PDFs usually contain long paragraphs, the text splitter allows AskPDF to process small chunks of paragraphs for analysis, while retrieval provides AskPDF with answers based on the provided PDF. 

![Image 2023-12-22 at 11 06 PM](https://github.com/jkmathilda/ChatGPT-Chatbot/assets/142202145/25da1fef-1ed8-40a8-a80b-de50aaf1c648)

# Getting Started

To get started with this project, you'll need to clone the repository and set up a virtual environment. This will allow you to install the required dependencies without affecting your system-wide Python installation.

### Cloning the Repository

    git clone https://github.com/jkmathilda/AskPDF.git

### Setting up a Virtual Environment

    cd ./AskPDF

    pyenv versions

    pyenv local 3.11.6

    echo '.env'  >> .gitignore
    echo '.venv' >> .gitignore

    ls -la

    python -m venv .venv        # create a new virtual environment

    source .venv/bin/activate   # Activate the virtual environment

    python -V                   # Check a python version

### Install the required dependencies

    pip install -r requirements.txt

### Configure the Application

To configure the application, there are a few properties that can be set the environment

    echo 'OPENAI_API_KEY="sk-...."' >> .env

### Running the Application

    python -m streamlit run app.py

### Deactivate the virtual environment

    deactivate

### Reference

Youtube : Create a ChatGPT For Your PDF in Python
[https://www.youtube.com/watch?v=wUAUdEw5oxM]