# Geocaching-ESP32-captive-portal


This project allows you to create a AP captive portal web interface. It provides a simple web page where you can toggle a somthing on gpio on and off.  This code can be changed for your uses.

## Features

- Toggle the gpio on and off.
- View the cache's uptime in settings.
- restart  the esp remotely in settings.
- version info in settings.
- onboard led indicates when client is connected
- buzzer beeps on boot

## Setup

To set up the ESP32 Cache project, follow these steps:

1. Connect the necessary hardware.
2. Upload the provided code to your ESP32 board.
3. after flashed connect to the esp Wi-Fi network, which will be named "UNNAMED".
4. or open a web browser and enter the IP address displayed on the ESP32's serial monitor.

## Usage

Once the ESP32 Cache project is set up, you can perform the following actions:

- Toggle the buzzer: Click the "Lock/unlock" button on the web interface to turn the buzzer on or off.
- View uptime: The web interface displays the cache's uptime in hours, minutes, and seconds.

## Customization

You can modify the HTML code in the `htmlPage` variable in the ESP32 sketch to customize the appearance of the web interface. Feel free to change the styling, content, or add additional features as needed.

## Dependencies

The ESP32 Cache project relies on the following libraries:

- [Arduino](https://www.arduino.cc/)
- [WiFi](https://github.com/espressif/arduino-esp32)
- [DNSServer](https://github.com/espressif/arduino-esp32/tree/master/libraries/DNSServer)
- [WebServer](https://github.com/espressif/arduino-esp32/tree/master/libraries/WebServer)
- [WiFiManager](https://github.com/tzapu/WiFiManager)


## Help
If Captive portal wont open. Open a web browser and enter the IP address displayed on the ESP32's serial monitor default is 192.168.1.50.

Why is it taking so long to connect and open? this problem has not been fixed yet and may be fixed in the future.
