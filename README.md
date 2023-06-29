# Chatbot

The Chatbot is a simple desktop application built using PyQt6 and OpenAI's GPT-3 model. It allows users to have interactive conversations with the chatbot by sending text messages and receiving responses.

## Features

- **Chat Interface**: The application provides a chat interface where users can send messages and view the bot's responses.
- **User Input**: Users can enter text messages in the input field and send them to the chatbot.
- **Bot Response**: The chatbot processes the user's input and generates a response using OpenAI's GPT-3 model.
- **Threaded Execution**: The chatbot responses are fetched in a separate thread to ensure smooth interaction with the user interface.
- **Styling**: The chat messages are styled with different colors to distinguish between user and bot messages.

## Requirements

The application requires the following dependencies:

- aiohttp==3.8.4
- aiosignal==1.3.1
- async-timeout==4.0.2
- attrs==23.1.0
- certifi==2023.5.7
- charset-normalizer==3.1.0
- colorama==0.4.6
- frozenlist==1.3.3
- idna==3.4
- multidict==6.0.4
- openai==0.27.8
- PyQt6==6.5.1
- PyQt6-Qt6==6.5.1
- PyQt6-sip==13.5.1
- requests==2.31.0
- tqdm==4.65.0
- urllib3==2.0.3
- yarl==1.9.2

Please refer to the [requirements.txt](requirements.txt) file for detailed version information.

## How to Run

To run the Chatbot:

1. Make sure you have the required dependencies installed in your Python environment.
2. Execute the `main.py` script using Python.
3. The Chatbot window will open, displaying the chat interface.
4. Type your message in the input field and press Enter or click the Send button to send it to the chatbot.
5. The chatbot will process the message and generate a response, which will be displayed in the chat area.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

We would like to acknowledge the developers and contributors of the open-source libraries used in this project. Their contributions and dedication have greatly facilitated the development of this Chatbot application. We express our gratitude to the following projects:

- [OpenAI](https://pypi.org/project/openai/)
- [PyQt6](https://pypi.org/project/PyQt6/)

Their efforts have played a vital role in making this project possible.