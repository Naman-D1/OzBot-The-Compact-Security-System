# Security System Project
A smart security system that uses computer vision to monitor live video feed and detect people/objects for improved safety.

## 🔒 Features
- Real-time detection
- Live camera feed
- Works with CCTV / USB camera
- Event logging and updates to phones
 
## 🛠️ Tech Stack
- Language: Python  
- Libraries:
    Pygame- hardware handling
    OpenCV- motion camera 
    Pyttsx3- TTS
    SpeechRecognition- STT
    Pyaudio- Speech Recognition prerequisite 
    Python_telegram bot- For telegram 
- Hardware: JRaspberry Pi / PC  

## ⚙️ How It Works
1. Camera captures live video  
2. Frames are processed using a detection model  
3. When a person/object is detected:
   - System logs the event  
   - Saves snapshot  

## 📂 Project Structure
    1. Camera detects Motion
    2. Expression is changed and Audio is recorded
    3. Owner's Input is taken
    4. Based on input, the visitor is asked to wait or leave
       - Is denied entry, the bot waits for 20 seconds, then sounds an alarm is motion is still detected.
