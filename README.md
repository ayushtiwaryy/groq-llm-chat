# Groq LLM Chat

A simple Python application that uses the Groq API to interact with the Llama 3.3 model.

## Features

- Uses the Groq Python SDK
- Loads the API key from a `.env` file
- Sends prompts to the LLM
- Prints the model response

## Project Structure

```
.
├── hello_llm.py
├── main.py
├── pyproject.toml
├── uv.lock
├── .gitignore
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/ayushtiwaryy/groq-llm-chat.git
```

Go to the project folder:

```bash
cd groq-llm-chat
```

Install dependencies:

```bash
pip install groq python-dotenv
```

## Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_api_key_here
```

## Run the project

```bash
python hello_llm.py
```

## Technologies Used

- Python
- Groq SDK
- python-dotenv

## Author

**Ayush Tiwary**

GitHub: https://github.com/ayushtiwaryy