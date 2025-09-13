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

Windows:

bash
pip install pipwin
pipwin install pyaudio

Linux:

bash
sudo apt-get install portaudio19-dev python3-pyaudio

Project Structure
Code
Hackathon/
├── main.py         # Main application logic
├── style.py        # Styling definitions (colors, fonts, emojis)

How to Run
Clone the repository:
bash
git clone https://github.com/Nutan-Excelr/Hackathon.git
cd Hackathon
Run the app:
bash
python main.py

Customization
1.You can easily modify the look and feel by editing style.py:
2.Change colors, fonts, emojis
3.Add new UI elements (buttons, menus)
4.Integrate additional voice models or export features
