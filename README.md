# Natural Language to SQL Query Generator

AI-powered tool that converts plain English business questions into SQL queries, enabling self-service analytics for non-technical stakeholders.

## Overview

AI-powered tool that converts plain English business questions into SQL queries, enabling self-service analytics for non-technical stakeholders.

## Live Demo

Try it here: **[tinosval-nlp-to-sql-generator-app-ccimdg.streamlit.app](https://tinosval-nlp-to-sql-generator-app-ccimdg.streamlit.app/)**

Paste in your own OpenAI API key in the sidebar to run it, ask a question in plain English and see the generated SQL query and result immediately.

## Problem Solved

- Eliminates IT dependency for data queries
- Reduces time-to-insight from days to seconds
- Empowers business users with self-service analytics

## Technologies Used

- Python
- OpenAI GPT-3.5
- SQLite
- Streamlit
- Pandas
- Plotly

## How It Works

1. User types question in plain English
2. AI generates appropriate SQL query
3. Query executes against database
4. Results display in readable format

## Sample Questions

- "Show me top 10 customers by revenue"
- "What is total sales by product category?"
- "Which city has the most orders?"
- "Show me monthly sales trend"

## Installation

### Prerequisites

- Python 3.9+
- OpenAI API key

### Steps

1. Clone the repository:
   ```
   git clone https://github.com/tinosval/nlp-to-sql-generator.git
   cd nlp-to-sql-generator
   ```
2. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```
3. Get your OpenAI API key from [platform.openai.com](https://platform.openai.com) and add it as an environment variable or directly in `app.py`, following the comment at the top of the file.
4. Run the app locally:
   ```
   streamlit run app.py
   ```
5. Streamlit will open the app in your browser, usually at `http://localhost:8501`.

## Author

Valentine Shedrach | Business Analyst

## GitHub Repository

[github.com/tinosval/nlp-to-sql-generator](https://github.com/tinosval/nlp-to-sql-generator)

## License

Open source for educational and commercial use.
