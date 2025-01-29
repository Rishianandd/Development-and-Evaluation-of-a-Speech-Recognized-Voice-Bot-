IEEE PAPER - https://ieeexplore.ieee.org/document/10465431


Development and Evaluation of a Speech-Recognized Voice Bot

Overview

Alpha is a voice-activated personal assistant developed in Python. It utilizes the speech_recognition library for voice command recognition and pyttsx3 for text-to-speech conversion. Alpha is designed to execute various tasks through simple voice commands, making desktop interactions more efficient and enjoyable.

Features

Voice Command Recognition: Uses speech_recognition for accurate speech input processing.

Text-to-Speech (TTS): Implements pyttsx3 for clear and responsive speech output.

Task Automation: Supports tasks such as:

Playing music on YouTube.

Fetching the latest news headlines.

Retrieving current weather updates.

Performing basic mathematical calculations.

Interactive Features:

Tells jokes.

Provides daily affirmations.

Responds to humorous questions.

Extensibility: Easily customizable to support new commands and features.

Applications

Personal Assistant: Automates daily tasks with voice commands.

Entertainment: Plays music and delivers engaging responses.

Productivity: Fetches news, weather, and performs quick calculations.

Accessibility: Assists users with hands-free control.

Installation

Clone the repository:

git clone https://github.com/username/Alpha-Voice-Bot.git
cd Alpha-Voice-Bot

Install dependencies:

pip install -r requirements.txt

Run the voice assistant:

python alpha.py

Usage

Start Alpha by running:

python alpha.py

Speak a command such as:

"Play music on YouTube"

"What's the weather today?"

"Tell me a joke"

Alpha will process the command and respond accordingly.

Directory Structure

Alpha-Voice-Bot/
├── src/
│   ├── alpha.py             # Main voice assistant script
│   ├── speech_recognition.py # Speech processing module
│   ├── tts_engine.py         # Text-to-Speech module
├── data/
│   ├── commands.json         # Predefined command mappings
├── requirements.txt         # Dependencies
├── README.md                # Documentation

Contributing

Contributions are welcome! Follow these steps:

Fork the repository.

Create a new branch:

git checkout -b feature-name

Commit your changes:

git commit -m 'Add new feature'

Push to the branch:

git push origin feature-name

Create a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Contact

For questions or feedback, reach out to:

Author: Rishi Anand

Email: rishianand@example.com
