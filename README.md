# Voice-Controlled Home Automation with Temperature and Humidity Monitoring
 
This project combines voice recognition with an Arduino setup to control home automation tasks and monitor environmental parameters such as temperature and humidity.

# Features
Voice Commands: Control your system using simple voice commands. The assistant can greet you, open files, report the temperature and humidity, and more.
Temperature and Humidity Monitoring: The system uses a DHT11 sensor to measure and report temperature and humidity, which can be accessed through voice commands.
Real-time Data Visualization: Environmental data is sent to a Blynk app for real-time monitoring and visualization.
Components

# Software:

Python for voice recognition and system interaction (speech_recognition, pyttsx3 libraries).
Arduino IDE for handling the sensor data and communication with the ESP8266 module.
Blynk app for monitoring.
Hardware:

Arduino/ESP8266 for microcontroller.
DHT11 sensor for temperature and humidity measurement.
Microphone for capturing voice commands.
ESP8266 module for Wi-Fi communication.
Setup Instructions
# Python Setup:

Install the required libraries: speech_recognition, pyttsx3.
Ensure your microphone is connected and recognized by the system.
Run the Python script to start the voice assistant.
Arduino Setup:

Connect the DHT11 sensor to your ESP8266 (D3 pin).
Load the Arduino sketch to the ESP8266 module.
Replace placeholders in the code with your Blynk authentication token, Wi-Fi credentials, and other configurations.
Monitor the temperature and humidity data in the Blynk app.
# Usage:

Start the Python script to initiate the voice assistant.
Use commands like "Hello," "Temperature," "Humidity," "Open," etc., to interact with the system.
# Voice Commands Supported
"Hello"
"Open [Directory]"
"Temperature"
"Humidity"
"Bye"
License
This project is open-source under the MIT License.
