# Chatbot with Google Cloud Natural Language API

This is a simple chatbot built with Python, Flask, and the spaCy NPL model. The chatbot is capable of finding the remander of a sentence in a website provided by the user. The code uses Flask along side an HTML file to create a local host where you can imput the question and website link.

## Features
- Fetches content from a specified URL using web scraping techniques
- Analyzes user queries using spaCy for natural language processing
- Generates responses based on the content of the web page

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your_username/your_repository.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Flask application:
   ```bash
   python Chatbot.py
   ```
2. Open your web browser and navigate to [http://localhost:5000](http://localhost:5000). You should see the chatbot interface.
3. Start interacting with the chatbot. Type a message in the input box and press Enter to see the response.

## Configuration
The chatbot configuration can be modified in the `Chatbot.py` file.
- Update the `url` variable with the URL of the web page you want to analyze.

## Troubleshooting
- If you encounter any issues, please check the console for error messages.
