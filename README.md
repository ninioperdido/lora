# Lora32 v2 Installation
1. Install the Arduino IDE.
2. Install the Heltec ESP32 library:
   Sketch -> Include Library -> Manage Libraries, search there "Heltec ESP32" and install it.
3. (Linux) Add permissions to the user: sudo usermod -a -G dialout $USER
4 . Add the additional board manager URL:
    File -> Preferences -> Additional Boards Manager URLs : https://github.com/Heltec-Aaron-Lee/WiFi_Kit_series/releases/download/0.0.6/package_heltec_esp32_index.json
5. Install the boards:
   Tools -> Board -> Boards Manager, search for Heltec ESP32 and install it.
6. Select "WiFi LoRa 32 v2" board.

