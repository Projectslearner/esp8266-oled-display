# ESP8266 OLED Display Project

#### Project Overview
This project demonstrates how to use an ESP8266 microcontroller to interface with an OLED display using the I2C protocol. The display can show text and numbers, making it useful for a variety of applications like displaying sensor data, messages, and more.

#### Components Needed
- **ESP8266 Microcontroller**
- **OLED Display (128x64 pixels)**
- **Jumper Wires**

#### Block diagram


#### Circuit Setup
1. **Connecting the OLED Display to ESP8266:**
   - Connect the SDA pin of the OLED display to the SDA (D2) pin on the ESP8266.
   - Connect the SCL pin of the OLED display to the SCL (D1) pin on the ESP8266.
   - Ensure proper power (VCC) and ground (GND) connections between the ESP8266 and the OLED display.

#### Instructions
1. **Setup:**
   - Open the Arduino IDE with ESP8266 board support installed.
   - Install the Adafruit SSD1306 and Adafruit GFX libraries via the Library Manager.
   - Create a new sketch and paste the provided Arduino code.
   - Connect the ESP8266 to your computer, select the appropriate board and port from the Tools menu.
   - Upload the code to the ESP8266.

2. **Operation:**
   - After uploading the code, the OLED display will show a "Hello, world!" message and a count number.
   - The text size and content can be customized in the code.

#### Applications
- **Sensor Display:** Show real-time data from various sensors.
- **System Information:** Display system status or messages.
- **Clocks and Timers:** Create clocks or countdown timers.

#### Notes
- **Initialization:** Ensure the correct initialization of the OLED display with the `SSD1306_I2C_ADDRESS`.
- **Text Size and Position:** Adjust the text size and cursor position as needed using `setTextSize` and `setCursor`.
- **Adafruit Libraries:** Make sure to install the required Adafruit SSD1306 and Adafruit GFX libraries for proper functionality.

---

#### Useful Links
🌐 [ProjectsLearner - ESP8266 OLED Display](https://projectslearner.com/learn/esp8266-oled-display)  
📧 [Email](mailto:projectslearner@gmail.com)  
📸 [Instagram](https://www.instagram.com/projectslearner/)  
📘 [Facebook](https://www.facebook.com/projectslearner)  
▶️ [YouTube](https://www.youtube.com/@ProjectsLearner)  
📘 [LinkedIn](https://www.linkedin.com/in/projectslearner)

Created with ❤️ by ProjectsLearner