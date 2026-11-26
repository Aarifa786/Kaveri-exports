# Kaveri Exports AI assistant

## About

Kaveri Exports AI Assistant helps Sales, HR, Admin, and Management teams access business information using AI. It has three components: a SQL Assistant that answers questions using business database information, a Document Assistant that retrieves answers from company documents with citations, and a Research Agent that searches external sources and provides relevant links.

## Setup

Create a virtual environment using python -m venv .venv and activate it using .venv\Scripts\Activate.ps1.

Install dependencies using pip install -r requirements.txt.

Copy .env.example to .env and enter your own configuration values. Never commit .env or API keys.

Run python load_db.py to build the database using files from data/raw/.

## Project layout

Folder

What is in it

src/

Source code for the AI assistant

prompts/

AI prompts and instructions

eval/

Evaluation datasets and results

docs/

Project documentation

tests/

Automated tests

data/

Raw datasets and database files