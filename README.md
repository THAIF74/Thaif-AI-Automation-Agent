
# Thaif AI Automation Agent 🤖

A customer-support email automation app built with Python and Streamlit.

## Features

- Classifies emails as Urgent / Angry, Account Issue, or Standard Query
- Assigns priority levels
- Routes emails to the appropriate support team
- Generates suggested customer replies
- Processes multiple emails through CSV upload
- Downloads classification results
- Offers Demo Mode without API credits
- Supports optional OpenAI-powered classification

## Technology Stack

- Python
- Streamlit
- Pandas
- OpenAI API
- python-dotenv

## Run Locally

1. Clone this repository.
2. Create and activate a virtual environment.
3. Install dependencies with `pip install -r requirements.txt`.
4. Run `python -m streamlit run app.py`.

## Live AI Mode

Configure `OPENAI_API_KEY` using a local `.env` file or Streamlit secrets.
An API key and available API credits are required.

Never commit secrets to GitHub.

## Limitations

This is a demonstration project. It does not send emails or connect to a real support ticketing system. Batch CSV processing uses keyword-based classification.

## Project Status

Built and tested locally before deployment.
