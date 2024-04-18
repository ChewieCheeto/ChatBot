Chatbot with Google Cloud Natural Language API
This is a simple chatbot built with Python, Flask, and the Google Cloud Natural Language API. The chatbot is capable of answering questions based on the content of a given web page.

Features
Fetches content from a specified URL
Analyzes the content using Google Cloud Natural Language API
Generates responses based on user queries
Provides a basic web interface for interaction
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your_username/your_repository.git
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Set up a Google Cloud project and enable the Cloud Natural Language API. Generate a service account key and download it as a JSON file.
Update the service_account_file variable in Chatbot.py with the path to your service account key JSON file.
Run the Flask application:
bash
Copy code
python Chatbot.py
Open a web browser and navigate to http://localhost:5000 to interact with the chatbot.
Usage
Enter a URL of the webpage you want to analyze.
Ask questions or provide queries to the chatbot.
The chatbot will generate responses based on the content of the webpage.
