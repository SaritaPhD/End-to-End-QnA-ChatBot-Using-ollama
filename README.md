# End-to-End-Q&A-ChatBot-Using-ollama

## Q&A Chatbot Using Ollama (Open Source Mistral)

This is a Q&A chatbot application built using Streamlit, Langchain, and Ollama. The chatbot leverages open-source models to generate responses based on user input.

## Features

- Select from open-source models for generating responses.
- Adjust response parameters such as temperature and maximum tokens.
- User-friendly interface for input and output.

## Requirements

- Python 3.10+
- Streamlit
- Mistal
- Langchain API Key
- Langchain
- Ollama
- dotenv

## Installation

1. **Clone the repository:**

    ```sh
    git clone git@github.com:SaritaPhD/End-to-End-QnA-ChatBot-Using-ollama.git
    cd End-to-End-QnA-ChatBot-Using-ollama
    ```

2. **Create and activate a virtual environment:**

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```sh
    pip install -r requirements.txt
    ```

4. **Set up environment variables:**

    Create a `.env` file in the root directory and add your Langchain API key and Langchain API key:

    ```env
    LANGCHAIN_API_KEY=your_langchain_api_key
    ```

## Usage

1. **Run the Streamlit app:**

    ```sh
    streamlit run app.py
    ```

2. **Navigate to the local server:**

    Open your web browser and go to `http://localhost:8501`.

3. **Interact with the chatbot:**

    - Select the model from the sidebar.
    - Adjust the response parameters (temperature and max tokens).
    - Enter your question in the text input field and get the response.

## Getting the "mistral" Model from Ollama

1. **Install Ollama:**

    ```sh
    pip install ollama
    ```

2. **Get the "mistral" Model:**

    To get the "mistral" model, run the following command in the terminal:

    ```
    ollama run mistral
    ```

## Project Structure

```plaintext
.
├── app.py
├── logger.py
├── exception.py
├── requirements.txt
├── .env
└── README.md
![alt text](<Screenshot 2024-07-31 at 1.20.21 PM.png>)