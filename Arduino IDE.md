# InstaNFC with Arduino IDE

## Setup

1. Download your preferred Arduino IDE from https://www.arduino.cc/en/software
2. In Preferences, add the following URL to `Additoinal Boards Manager URLs`: https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
3. Install the Arduino Core from Espressif in  `Tools` > `Board: "----"` > `Boards Manager` > Search `esp` > Install `esp32`
4. Connect hardware via USB
5. In `Tools` select the correct `Port`, for example `"/dev/cu.subserial-145110"`
6. In `Tools` choose the following additional options:
    * Board: "ESP32 Dev Module"
    * Upload Speed: "921600"
    * Flash Frequency: "80MHz"
    * Flash Size: "16MB"
    * Partinion Scheme "Minimal SPIFFS" (if you would like OTA to work)
7. Click upload, the board will be flashed and rebooted automatically 

## Start Coding

Sample code for Access Pro boards can be found here: https://github.com/InstaNFC/P01.12V-2021.11/tree/main/Arduino%20Samples
