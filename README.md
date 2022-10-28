# controlling-IOT-with-Alexa-with-extra-manual-switch-
The circuitry will be as follows,
VCC-VCC,GND-GND
I have used D23, D22, D21, D19, D18, D5, D25 & D26 GPIO to control the 8-channel relay module.
And the GPIO D13, D12, D14, D27, D33, D32, D15 & D4 are connected with manual switches to control the relay module manually.
I have used the INPUT_PULLUP function in Arduino IDE instead of using the pull-up resistors with each switch.
As per the source code, when the control pins of the relay module receive the LOW signal the respective relay will turn on and the relay will turn off for the HIGH signal in the control pin.

Components as be followed by 

ESP32 DEV KIT V1
8-channel 5V SPDT Relay Module
Manual Switches
Amazon Echo Dot

Program ESP32 with Arduino IDE
In the Tutorial video, I have explained all the steps to program the ESP32 DEV KIT V1 using Arduino IDE.

Update the Preferences –> Aditional boards Manager URLs: https://dl.espressif.com/dl/package_esp32_index.json, http://arduino.esp8266.com/stable/package_esp8266com_index.json

Then install the ESP32 board from the Board manager or Copy here https://github.com/espressif/arduino-esp32 to download the ESP32 board.
Download the required libraries from the Arduino software or update
Espalexa Library
AceButton Library ![ESP32-Alexa-Pic-10]

for other/app interface follow this link
(https://user-images.githubusercontent.com/109905492/198602477-f74cce12-fff8-4f19-a6bb-03468b7843f0.jpg)
