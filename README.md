# Text Summarizer

## Overview
This is a Text Summarization web application built using FastAPI and the T5 Transformer model. It generates concise summaries from long pieces of text using Natural Language Processing (NLP).

## Features
- Summarizes long text into shorter summaries
- FastAPI-based web application
- User-friendly web interface
- Transformer-based text summarization using T5

## Tech Stack
- Python
- FastAPI
- PyTorch
- Hugging Face Transformers
- HTML

## Project Structure
```
TextSummarizerApp/
├── app.py
├── templates/
│   └── index.html
├── README.md
└── .gitignore
```

## How to Run
1. Clone the repository.
2. Install the required dependencies.
3. Run:
   ```
   python app.py
   ```
4. Open the application in your browser.

## Note
The trained model (`saved_summary_model`) is not included in this repository because it exceeds GitHub's file size limit.