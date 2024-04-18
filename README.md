# Chatbot with Google Cloud Natural Language API

This is a simple chatbot built with Python, Flask, and the Google Cloud Natural Language API. The chatbot is capable of answering questions based on the content of a given web page.

## Features

- Fetches content from a specified URL
- Analyzes the content using Google Cloud Natural Language API
- Generates responses based on user queries
- Provides a basic web interface for interaction

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your_username/your_repository.git
```
2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

3. Run the Flask application:
```bash
python Chatbot.py
```

- Open your web browser and navigate to http://localhost:5000. You should see the chatbot interface.
- Start interacting with the chatbot. Type a message in the input box and press Enter to see the response.

## Configuration

- The chatbot configuration can be modified in the Chatbot.py file.
- Update the google_api_key variable with your Google Cloud API key.
- Update the url variable with the URL of the web page you want to analyze.
  
## Troubleshooting
- If you encounter any issues, please check the console for error messages.
- Ensure that you have set up the Google Cloud project correctly and enabled the Cloud Natural Language API.
