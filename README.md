# Gemini AI Text Summarizer

An AI-powered text summarization application built using Python and Google's Gemini LLM.

## Project Overview

This project takes input text from a text file and uses the Gemini API to generate a concise summary while preserving the important information.

## Technologies Used

- Python
- Google Gemini API
- Large Language Models (LLMs)
- Prompt Engineering
- python-dotenv

## Project Structure

```text
aiproject/
├── main.py
├── sample.txt
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

## Features

- Reads text from a file.
- Integrates with Google's Gemini LLM.
- Uses prompts to generate summaries.
- Secure API key management using environment variables.

## Installation

1. Clone the repository.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Create a `.env` file and add your Gemini API key:

```env
GEMINI_API_KEY=your_api_key
```

4. Run the application:

```bash
python main.py
```

## Learning Outcomes

- Understanding LLM integration.
- Working with API requests and responses.
- Prompt engineering.
- Python environment variables.
- Git and GitHub version control.

## Future Improvements

- User-provided text input.
- Customizable summary lengths.
- PDF document summarization.
- Long-document processing using chunking.
- RAG integration.

## Author

AI Engineering Learner