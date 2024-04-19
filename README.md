# Voice-Assistant
# Voice Assistant

This is a Python script that implements a voice assistant named Alexa. It uses the following libraries and APIs:

- `pyttsx3`: A text-to-speech conversion library.
- `speech_recognition`: Library for performing speech recognition.
- `datetime`: For handling date and time.
- `wikipedia`: For searching and retrieving information from Wikipedia.
- `webbrowser`: For opening web browsers.
- `os`: For interacting with the operating system.
- `smtplib`: For sending emails.
- `pyjokes`: For fetching jokes.
- `requests`: For sending HTTP requests.
- `BeautifulSoup`: For parsing HTML.

## Features

- **Voice Recognition**: Alexa can understand voice commands using the `speech_recognition` library.
- **Wikipedia Search**: You can ask Alexa to search for information on Wikipedia.
- **Web Browsing**: Alexa can open YouTube, Google, and Stack Overflow in your default web browser.
- **Time**: Alexa can tell you the current time.
- **Jokes**: Alexa can tell jokes.
- **News**: Alexa can fetch and read headlines from BBC News.
- **Email**: You can ask Alexa to send emails.
- **Weather**: Alexa can provide weather information for a given city.

## Usage

1. Make sure you have Python installed on your system.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the script using `python filename.py`.
4. Alexa will greet you and wait for your command. You can speak your command, and Alexa will respond accordingly.

## Additional Notes

- You need an active internet connection for some functionalities like fetching Wikipedia information, sending emails, and fetching news headlines.
- Make sure to configure the email credentials in the script before using the email functionality.
- The weather functionality uses Google search to fetch weather information, so it may not work if Google changes its page structure.

Feel free to explore and modify the script according to your requirements!

