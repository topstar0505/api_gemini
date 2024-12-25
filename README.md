# Flask Web Service for Gemini API

## Set Up a Virtual Environment

1.	Create a virtual environment to isolate your project dependencies:

`python -m venv venv`

2.	Activate the virtual environment:

- Windows

`venv\Scripts\activate`

- Linux & MacOS

`source venv/bin/activate`

3. Install Required Packages

- Windows

`pip install -r requirements.txt`

- Linux & MacOS

`pip3 install -r requirements.txt`

4. Gemini API Key

- Create a Google Account.

If you don’t already have one, sign up for a Google account.

- Access Google AI Studio.

Go to the Google AI Studio by searching for "Google AI for Developers" or directly visiting the relevant page.

- Get the API Key

Click on the “Get API key in Google AI Studio” button.

You will be prompted to review and accept the terms of service. Make sure to consent to the necessary agreements.

After that, you can choose to create an API key in a new project or an existing one.

- Generate Your API Key

Click on “Create API key.” Your key will be generated automatically, and you should copy it immediately for secure storage, as it is essential for accessing the Gemini services.

- Set GEMINI_API_KEY in the .env file.

`GEMINI_API_KEY='AI***'`

## Run

- Windows

`python gemini.py`

- Linux & MacOS

`python3 gemini.py`

## API Test

GET `/localhost:5000/google`

POST `/localhost:5000/google`

