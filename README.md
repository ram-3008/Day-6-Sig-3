Day-6: Control LED Through Web Browser
This project demonstrates how to control the ESP32’s built-in LED using a simple web page. The ESP32 connects to the Wokwi virtual WiFi network and runs a web server that provides options to turn the LED ON or OFF.

Hardware
ESP32 DevKit v1 Built-in LED connected to GPIO 2 No external components are required. WiFi Configuration Network: Wokwi-GUEST Password: Leave blank Wokwi Simulation

Run the simulation

How to Use
Start the ESP32 simulation in Wokwi. Open the Serial Monitor. Wait until the ESP32 successfully connects to the WiFi network. Copy the IP address displayed in the Serial Monitor. Open the IP address in a web browser that can access the Wokwi simulation. The web page will display options to control the LED. Click LED ON to turn the built-in LED on. Click LED OFF to turn the LED off.

Web Server
The ESP32 runs a web server on port 80.

The following routes are used to control the LED:

/ledon → Turns the LED ON /ledoff → Turns the LED OFF

This project shows how an ESP32 can be connected to WiFi and controlled remotely through a web browser.

Wokwi Simulation:https://wokwi.com/projects/476656307968310273
