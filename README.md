# Smart_Watering_System
This is my Deliverable1 for IT254. My project will send a notification via the Telegram app, to remind the user to water their plan when soil moisture is detected as low.
## Project Requirements

| Component                    | Type       | Version/Specification | Description                                                                                   |                              |            |                       |
|------------------------------|------------|-----------------------|-----------------------------------------------------------------------------------------------|                              |            |                       |
| Arduino Board                | Hardware   | Uno or Nano           | Main microcontroller to control the system.                                                   |                              |            |                       |
| Soil Moisture Sensor         | Hardware   | SparkFun or similar   | Measures soil moisture level. Be sure to connect the analog output to the Arduino analog pin. |                              |            |                       |
| Bluetooth Module (HC-06)     | Hardware   | HC-06                 | Enables wireless communication with the bot via a Bluetooth-enabled device.                   |                              |            |                       |
| Python                       | Software   | 3.8+                  | Required for handling Telegram bot integration and data processing.                           |                              |            |                       |      
| Arduino IDE                  | Software   | 1.8.13+               | Used for programming the Arduino board.
|                              |            |                       |
| PySerial Library             | Software   | Latest                | Python library for serial communication between Python and Arduino.  
|                              |            |                       |
| Python telegram Bot Library  | Software   | Latest                | Python library for programming Telegram Bot.       
|                              |            |                       |
| Telegram Bot API Token       | API Key    | N/A                   | Necessary for interacting with Telegram bot. Make sure to keep it private.                    

### Potential Hidden Issues
- **General Hardware:** Ensure sensors/hardwear is not damaged in any way. Any type of damage could break the project.
- **HC-06 Baud Rate:** Ensure the HC-06 baud rate is set to 9600 by default, or else it may cause communication issues.
- **HC-06 Baud Connected:** Verify that the HC-06 is connected via bluetooth to your device. Password is usually '1234' or '0000'
- **Soil Moisture Sensor Connections:** Ensure jumper wires are screwed in enough in screw terminal, and make sure they are connected properly on Arduino (A0, GND, 3.3v.
- **COM Port Configuration:** Ensure the correct COM port is specified in the Python script for serial communication.
- **Python Environment:** If using virtual environments, activate it correctly and ensure all required packages are installed within it.
- **Telegram Bot Permissions:** Ensure your bot has permission to read and respond to messages.
- **Telegram Bot Commands:** Ensure your bot's commands are set up correctly, both in Telegram and Python.
- **Telegram Bot Token:** Ensure your bot's API token is not lost or incorrect. You will get the Token from Bot Father, nowhere else.


