# Chat Translation Application with Gemini API

This project is a chat application that allows users to send and receive messages in multiple languages. The application uses the Google Gemini API to translate messages between English and Spanish. It also interacts with a MySQL database to store and retrieve chat messages, providing a multilingual chat experience with real-time translation.

## Features

- **Send Messages**: Users can enter messages and choose their output language (English or Spanish).
- **Real-Time Translation**: Messages from the database are translated between English and Spanish based on the user's selection.
- **Chat History**: The chat history is fetched from the MySQL database and displayed in the chat window.
- **Database Integration**: The application connects to a MySQL database to store and retrieve chat messages.

## Requirements

- Python 3.x
- `google-generativeai` (Gemini API)
- `mysql-connector-python`
- `tkinter` (for GUI)
- `pygame` (for additional functionalities, if required)

You can install the necessary libraries using pip:

```bash
pip install google-generativeai mysql-connector-python pygame

```

## Setup
1. Gemini API Key: To use the Google Gemini API, you’ll need to insert your API key into the code. You can get your key from the Gemini API Documentation.
2. Database Configuration: Insert your MySQL database host, username, password, and database name values into the code where indicated.:
```python
host = 'your_database_host'
user = 'your_database_user'
password = 'your_database_password'
database = 'your_database_name'
```
3. Run the Application: The app provides a graphical interface using tkinter where you can:
	•	Input your username.
	•	Choose the output language (Spanish or English).
	•	View the chat history, with translations between languages.
	•	Send messages, which are saved to the MySQL database.

## How to Use
1. Start the Application: Run the Python script to launch the application window.
2. Enter Username: Input your username in the provided entry field.
3. Select Output Language: Choose between “English” or “Spanish” for the translated chat output.
4. Send a Message: Type your message in the text box and press “Send”. The message will be stored in the database and displayed in the chat window.
5. View Translated Messages: Click on the “Refresh” button to retrieve and display new messages, with automatic translation based on your selected language.
