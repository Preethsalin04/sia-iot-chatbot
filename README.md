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


## Installation
-  **Install packages
-  import json
import numpy as np
import webbrowser
import os
from tensorflow.keras.models import Sequential, load_model
from tensorflow.keras.layers import Dense, Embedding, LSTM, GlobalMaxPooling1D
from tensorflow.keras.preprocessing.text import Tokenizer
from tensorflow.keras.preprocessing.sequence import pad_sequences
from sklearn.preprocessing import LabelEncoder
from gtts import gTTS
import pygame
import uuid
import random
import speech_recognition as sr
import time
import warnings
import wave
warnings.filterwarnings("ignore")
### Prerequisites
- Python 3.8 or higher
- Microphone (for voice mode)

### Setup
1. Clone the repository:
```bash
git clone https://github.com/yourusername/chatbot-project.git
cd chatbot-project
