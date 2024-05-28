

# Llama2 Medical Bot

The Llama2 Medical Bot is a powerful tool designed to provide medical information by answering user queries using state-of-the-art language models and vector stores. This README will guide you through the setup and usage of the Llama2 Medical Bot.

## Table of Contents

- [Introduction](#langchain-medical-bot)
- [Table of Contents](#table-of-contents)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Output](#output---chainlit)

## Prerequisites

Before you can start using the Llama2 Medical Bot, make sure you have the following prerequisites installed on your system:

- Python 3.6 or higher
- Required Python packages (you can install them using pip):
    - langchain
    - chainlit
    - sentence-transformers
    - faiss
    - PyPDF2 (for PDF document loading)

## Installation

1. Clone this repository to your local machine.

    ```bash
    git clone https://github.com/your-username/langchain-medical-bot.git
    cd langchain-medical-bot
    ```

2. Create a Python virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use: venv\Scripts\activate
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Download the required language models and data. Please refer to the Langchain documentation for specific instructions on how to download and set up the language model and vector store.

5. Set up the necessary paths and configurations in your project, including the `DB_FAISS_PATH` variable and other configurations as per your needs.

## Output - ChainLit

