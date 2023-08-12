# Speech-to-Text and Text-to-Speech with ChatGPT Example

This GitHub repository contains an example project that demonstrates how to use the Python SpeechRecognition library to capture spoken words, convert them into text, send the text to the ChatGPT API for generating a response, and then convert the response text back into speech using the Google Text-to-Speech Python library.

## Prerequisites

Before you begin, make sure you have the following prerequisites installed:

- Python 3.x
- `pip` package manager
- Google Text-to-Speech library (`gTTS`)
- SpeechRecognition library (`speech_recognition`)
- Your own ChatGPT API key (sign up at https://www.openai.com/)

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/speech-to-text-chatgpt-text-to-speech.git
   cd speech-to-text-chatgpt-text-to-speech
   ```

2. Install the required Python packages using pip:

    ```bash
    pip install gTTS speech_recognition
    ```

## Usage
Replace 'YOUR_CHATGPT_API_KEY' in the main.py file with your actual ChatGPT API key.

Run the main.py script:

    ```bash
    python main.py
    ```

The program will prompt you to speak. After speaking, it will convert your speech into text using the SpeechRecognition library.

The converted text will be sent to the ChatGPT API, and you will receive a response from ChatGPT.

The response text will be transformed into speech using the Google Text-to-Speech library and played back to you.

## Customization
Feel free to customize and expand this example project according to your needs. You can modify the prompts, responses, and interaction logic in the main.py script. You can also explore additional features such as handling different languages, error handling, or integrating with other text-to-speech engines.

## Limitations
Please note that this example project focuses on demonstrating the integration of various libraries and APIs. The accuracy and quality of speech recognition and generation may vary based on factors such as background noise, microphone quality, and API response.

Usage of the ChatGPT API may incur costs based on the usage and pricing structure of the OpenAI platform.

## Acknowledgments
This project builds upon the capabilities of the following libraries and services:

* Python SpeechRecognition library
* Google Text-to-Speech (gTTS) library
* OpenAI's ChatGPT API

## Disclaimer
This project is provided as an example and does not guarantee perfect results. The performance of speech recognition and text-to-speech generation may vary based on external factors.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it according to the terms of the license.

Feel free to contribute to this project, report issues, or suggest improvements. Your feedback is greatly appreciated!