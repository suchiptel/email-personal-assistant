# Email Personal Assistant

This project creates a personalized email assistant using Named Entity Recognition (NER) and Retrieval-Augmented Generation (RAG) based on GPT. It fetches emails, extracts key entities, retrieves past email interactions, and generates personalized replies.

## Features

- Fetches emails using IMAP
- Uses NER to extract relevant entities (names, dates, organizations)
- FAISS-based document retrieval to find past relevant emails
- RAG model for generating personalized responses
- Fine-tuning GPT to match user email behavior

## Installation

1. Clone the repository:
    ```
    git clone https://github.com/your-username/email-personal-assistant.git
    ```

2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```

3. Add your email credentials in the `src/fetch_emails.py`.

## Usage

Run the main script to start fetching emails, extracting entities, and generating responses:
