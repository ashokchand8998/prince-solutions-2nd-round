Project Name: Prince Solutions Chat Server

Description:

This repository provides a Flask-based chat server and UI, enabling real-time chat interactions.

Prerequisites:

Python 3.11.4 (or a compatible version) - Download from https://www.python.org/downloads/
Git version control system - Download from https://www.git-scm.com/ (https://www.git-scm.com/downloads)

Installation:

1) Clone the repository:


git clone https://github.com/ashokchand8998/prince-solutions-2nd-round.git
cd prince-solutions-2nd-round



2) Create a virtual environment (recommended):

python3 -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate.bat  # For Windows

3) Install required packages:


pip install -r requirements.txt



Running the Server:

4) Start the chat server using:

python chat_server.py


Access the chatbot:
Open a web browser and navigate to the default server IP address followed by the port number specified in chat_server.py (usually localhost:5000).
For example, if the port number is 5000, you'd access the chatbot at http://localhost:5000/.
