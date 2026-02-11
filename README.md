# sia-iot-chatbot
AI-powered chatbot that supports both voice and text-based interactions. It uses Natural Language Processing (NLP), speech recognition, and text-to-speech (TTS) to provide a seamless conversational experience. The chatbot can predict user intents, respond intelligently, and even speak back using generated audio responses.
# AI ChatBot with Voice and Text Interface

An intelligent chatbot with both voice and text interaction capabilities, built using TensorFlow/Keras for natural language processing.

## Features

- 🤖 **Dual Mode Interaction**: Switch between voice and text input
- 🎤 **Speech Recognition**: Built-in voice recognition using Google Speech API
- 🔊 **Text-to-Speech**: Voice responses using gTTS
- 🧠 **Neural Network**: LSTM-based intent classification model
- ⚡ **Real-time Processing**: Instant response generation
- 🔄 **Retraining Capability**: Easy model retraining with custom epochs
- 💾 **Model Persistence**: Saves trained model for future use


### Installation
Create a requirements.txt file:
```bash
** tensorflow>=2.10.0
** numpy>=1.21.0
** gTTS>=2.3.0
** pygame>=2.1.0
** SpeechRecognition>=3.10.0
** scikit-learn>=1.0.0
** textblob>=0.17.1  # For sentiment analysis
** python-dateutil>=2.8.2  # For date handling
** pydub>=0.25.1  # For audio processing
```
# Open Command Prompt as Administrator
# Install dependencies
```bash
## Windows
# 1. Install Python (3.8 or higher)
# Download from python.org
# 2. Open Command Prompt as Administrator
# 3. Install dependencies
python -m pip install --upgrade pip
pip install tensorflow-cpu numpy scikit-learn gTTS pygame SpeechRecognition
# 4. For TensorFlow with GPU support (if you have NVIDIA GPU):
pip install tensorflow

## Ubuntu
## Install Python packages:
pip3 install tensorflow-macos numpy scikit-learn gTTS pygame SpeechRecognition
Linux (Ubuntu/Debian)
# 1. Update package list
sudo apt update
# 2. Install system dependencies
sudo apt install python3 python3-pip python3-dev portaudio19-dev
# 3. Install Python packages
pip3 install tensorflow numpy scikit-learn gTTS pygame SpeechRecognition
# 4. Fix pygame sound issues (if any):
sudo apt install libsdl2-mixer-2.0-0 libsdl2-image-2.0-0 libsdl2-2.0-0

## macOS
# 1. Install Homebrew if not installed:
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
# 2. Install Python:
brew install python
# 3. Install PortAudio for microphone support:
brew install portaudio
# 4. Install Python packages:
pip3 install tensorflow-macos numpy scikit-learn gTTS pygame SpeechRecognition
```
### Setup
1. Clone the repository:
```bash
git clone https://github.com/yourusername/chatbot-project.git
cd chatbot-project
python app.py
```
## Hardware Requirements 
* - Raspberry Pi 5
  - Speaker
