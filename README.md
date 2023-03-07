# 👋 Hi there!

This is a code file for a ESP32 board that enables communication over WiFi using WebSockets. The code reads audio data from an I2S microphone and sends it to a client over the WebSocket connection, and it also receives audio data from the client and plays it back through an I2S speaker.

# ✨ Features:

Supports audio transmission over WiFi using WebSockets
Uses I2S to interface with an audio codec
Sends and receives audio data in binary format
Can be controlled with a single button press (speak/listen mode)
# 🚀 Getting Started:

Set up your ESP32 development environment
Add the required libraries to your project (ArduinoWebsockets.h, Button2.h)
Connect an I2S microphone and speaker to the ESP32 board
Adjust the pin numbers in the code to match your hardware configuration
Compile and upload the code to your ESP32 board
Connect to the ESP32's WiFi network and open the client webpage in a browser
# 💡 Usage:

Press the button to switch between speaking and listening modes
In speaking mode, speak into the microphone and the audio will be transmitted to the client
In listening mode, the ESP32 will play back audio received from the client through the speaker
# 📚 References:

ArduinoWebsockets library: https://github.com/gilmaimon/ArduinoWebsockets

Button2 library: https://github.com/LennartHennigs/Button2

ESP32 I2S example: https://github.com/espressif/arduino-esp32/blob/master/libraries/ESP32/examples/I2S/I2S.ino
