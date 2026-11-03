# Hugging Face Pipelines – Multi-Task NLP Application

## Overview

This project is a Natural Language Processing (NLP) application developed using Python, Streamlit, and Hugging Face Transformers. It demonstrates how pretrained transformer models can perform different language processing tasks through a simple and interactive web interface.

The application integrates four Hugging Face pipelines for text summarization, language translation, sentiment analysis, and question answering.

## Features

### 1. Text Summarization
- Converts long paragraphs into shorter summaries.
- Preserves the main ideas and important information.
- Uses a pretrained transformer model for automatic summarization.

### 2. Language Translation
- Translates text from English into French.
- Uses a pretrained neural machine translation model.
- Demonstrates multilingual text processing.

### 3. Sentiment Analysis
- Analyzes the emotional polarity of sentences and text.
- Classifies input as positive or negative.
- Displays the predicted label and confidence score.

### 4. Question Answering
- Accepts a passage and a question from the user.
- Extracts a relevant answer from the provided passage.
- Displays the answer and its confidence score.

## Technologies and Libraries

- Python – Application programming
- Hugging Face Transformers – Pretrained NLP models and pipelines
- Streamlit – Interactive web interface
- PyTorch – Deep learning model execution
- SentencePiece – Tokenization support for translation models

## Project Structure

```text
llm-week-7/
├── app.py
├── requirements.txt
└── README.md
```

## Installation and Setup

### Prerequisites

- Python 3.10 or later
- Visual Studio Code
- Internet connection for downloading pretrained models

### Step 1: Create a Virtual Environment

```bash
python3 -m venv venv
```

Activate the environment on macOS:

```bash
source venv/bin/activate
```

### Step 2: Install Dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### Step 3: Launch the Application

```bash
streamlit run app.py
```

Open the local URL displayed in the terminal to access the application in your browser.

## Hugging Face Models

| NLP Task | Pretrained Model |
|---|---|
| Summarization | `sshleifer/distilbart-cnn-12-6` |
| Translation | `Helsinki-NLP/opus-mt-en-fr` |
| Sentiment Analysis | `distilbert/distilbert-base-uncased-finetuned-sst-2-english` |
| Question Answering | `distilbert/distilbert-base-cased-distilled-squad` |

## Learning Outcomes

- Understanding the purpose and usage of Hugging Face pipelines.
- Integrating pretrained transformer models into Python applications.
- Performing multiple NLP tasks using a unified interface.
- Understanding text classification, translation, summarization, and extractive question answering.
- Developing an interactive application using Streamlit.

## Applications

- Summarizing lengthy study materials and articles.
- Translating English text into French.
- Analyzing customer reviews and written feedback.
- Finding answers from documents and educational passages.
- Demonstrating practical applications of transformer-based NLP.

## Future Enhancements

- Add translation support for more languages.
- Enable document uploads for summarization and question answering.
- Allow users to download generated summaries and analysis results.
- Improve the interface with chat history and additional controls.
- Add support for more NLP tasks and pretrained models.

## Conclusion

This project demonstrates the use of Hugging Face Transformers pipelines to simplify the implementation of common Natural Language Processing tasks. By combining four pretrained models with Streamlit, the application provides an accessible way to explore practical NLP techniques through an interactive web interface.

