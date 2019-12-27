Hello and welcome to my email assistant project!
I decided to create this project due to the large numbers of emails
I receive on a daily bases. I wanted a simple "assistant" that could 
help me keep track of my emails. 

Version 1.0 --
This version listens for a "check emails" command and returns emails
in my "unread" emails folder on my gmail account. 

To create an assistant with 3 main goals:
    1. Understand a speech command
        a. Using SpeechRecognition (https://pypi.org/project/SpeechRecognition/)
    2. Read Google email
        a. Using Google API (https://developers.google.com/gmail/api/quickstart/js)
    3. Speech response to commands
        a. Using gtts (https://pypi.org/project/gTTS/) 