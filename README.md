# AskPDF


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

    python -m streamlit run main.py

### Deactivate the virtual environment

    deactivate

### Reference

Chatbots (on LangChain)
[https://python.langchain.com/docs/use_cases/chatbots]

Youtube : Create a ChatGPT clone using Streamlit and LangChain
[https://www.youtube.com/watch?v=IaTiyQ2oYUQ]