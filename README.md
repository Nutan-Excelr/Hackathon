Features
1.Real-time voice-to-text transcription using Google Speech Recognition
2.Chat-style UI with role-based color coding (You/System)
3.Modular styling via style.py for easy theme customization
4.Responsive layout with header, chat area, and status bar
5.Non-blocking speech recognition using threading

Requirements
Make sure you have Python 3.7+ installed. Then install the required packages:

bash
pip install SpeechRecognition
pip install PyAudio
On some systems, installing PyAudio may require additional setup:

Windows: Use pip install pipwin && pipwin install pyaudio
Linux: sudo apt-get install portaudio19-dev python3-pyaudio

Project Structure
Code
voice_chat/
├── main.py         # Main application logic
├── style.py        # Styling definitions (colors, fonts, emojis)
🚀 How to Run
Clone the repository:

bash
git clone https://github.com/your-username/voice_chat_app.git
cd voice_chat_app
Run the app:

bash
python main.py

Customization
You can easily modify the look and feel by editing style.py:
Change colors, fonts, emojis
Add new UI elements (buttons, menus)
Integrate additional voice models or export features
