# WEB-EXTRACT-AI
 The objective is to create an AI-powered tool that automates web-based information retrieval using user-defined queries for entities in a dataset. It integrates data processing and NLP to extract relevant insights efficiently, offering a seamless workflow via a dashboard for data upload, query input, and structured result display.
AI-Powered Web Data Extraction Tool
Overview
This project is an AI-powered tool that automates information retrieval from web sources based on user-defined queries for specific entities in a dataset. The tool uses natural language processing and web scraping to deliver structured insights in an intuitive dashboard.

Features
Upload Data: Upload CSV files or connect to Google Sheets to input data.
Custom Queries: Define specific prompts for retrieving information using placeholders (e.g., {company}).
Automated Web Search: Perform web searches for each entity, integrating APIs like SerpAPI for reliable results.
AI-Driven Parsing: Use an LLM (e.g., OpenAI GPT) to extract specific information from search results.
Data Visualization: Display extracted information in a tabular format and allow downloading as a CSV or updating Google Sheets.
Requirements
Python 3.10+
Google Colab environment (for running the project)
APIs:
SerpAPI
OpenAI GPT
Google Sheets API
Installation
Clone the repository:

bash
Copy code
git clone <repository-url>
Install the dependencies:

bash
Copy code
pip install -r requirements.txt
Set up API keys:

SerpAPI: Sign up at SerpAPI and get an API key.
OpenAI: Get an API key from OpenAI.
Google Sheets: Enable the Google Sheets API and download credentials JSON.
Upload the project to Google Colab and ensure all dependencies are installed.

Usage
Run the main notebook in Google Colab.
Upload a CSV file or connect a Google Sheet via the dashboard.
Select the primary column for query generation.
Define a custom query template using placeholders.
View, download, or save the structured results.
File Structure
main.ipynb: Primary notebook for running the tool in Google Colab.
dashboard.py: Backend and UI logic for the dashboard.
api_integration.py: Handles API calls for SerpAPI, OpenAI, and Google Sheets.
utils/: Helper functions for data processing.
