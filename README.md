# AI Assistant

This repository contains the Python code for a voice-activated AI Assistant designed to streamline everyday tasks through voice commands. The assistant combines natural language processing, text-to-speech capabilities, and automation tools to deliver a user-friendly experience.

## Features

### 1. Voice Interaction
- Recognizes and processes user commands using the `speech_recognition` library.
- Responds via text-to-speech powered by `pyttsx3`.

### 2. Customizable Greetings
- Offers personalized, time-based greetings.
- Utilizes current day and time for tailored interaction.

### 3. Task Automation
- Opens and closes desktop applications like Notepad, Calculator, and Paint.
- Handles web-based tasks such as opening social media platforms or performing Google searches.

### 4. Daily Schedule
- Recites predefined schedules for each day of the week, keeping you organized.

### 5. System Monitoring
- Reports CPU usage and battery status.
- Provides guidance for optimal system performance.

### 6. Natural Language Understanding
- Processes user queries using a trained TensorFlow model for intent recognition.
- Responds dynamically based on a JSON-based intent structure.

### 7. Volume Control
- Adjusts system volume directly through voice commands.

## Prerequisites
- Python 3.7+
- Required Libraries:
  - `pyttsx3`
  - `speech_recognition`
  - `numpy`
  - `tensorflow`
  - `psutil`
  - `pyautogui`
  - `webbrowser`
- Pretrained models and files:
  - `chat_model.h5`
  - `tokenizer.pkl`
  - `label_encoder.pkl`
  - `intents.json`

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ai-assistant.git
   cd ai-assistant
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the script:
   ```bash
   python assistant.py
   ```

4. Use voice commands to interact with the assistant.

## Example Commands
- "Open Facebook"
- "What is my schedule for today?"
- "Check the system condition"
- "Increase the volume"
- "Open Calculator"
- "Exit"


