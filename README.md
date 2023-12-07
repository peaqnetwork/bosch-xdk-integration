# XDK MQTT Application

Welcome to the XDK MQTT application (integrating Bosch XDK with peaq network). This code is an example of an application built using Eclipse Mita. It involves interactions with MQTT messaging and control of lighting using XDK 110.

## Getting Started

To run this application on your XDK 110, follow these steps:

1. Ensure that you have the XDK Workbench installed and set up.

3. Open the project in XDK Workbench.

4. Make sure you have your XDK 110 connected to your computer.

5. Modify the necessary parameters in the code, such as `ssid`, `psk`, `deviceID`, and MQTT broker information.

6. Build and flash the application to your XDK 110 device.

7. Observe the application behavior based on the code logic.



## Code Overview

- The application establishes connections to MQTT broker and WLAN network.
- It reads various sensor data like temperature, humidity, and light intensity.
- It publishes this sensor data to an MQTT topic named `telemetry`.
- The application also allows you to control a home light using a button press.
- It communicates with the broker and sends a device ID to a topic named `deviceID` upon button press.

## Configuration

Before running the application, make sure to configure the following:

- Set your WiFi SSID and authentication details in the `net` setup.
- Configure the MQTT broker URL and client ID in the `mqtt` setup.
- Update the `deviceID` to your unique identifier.

## Dependencies

- This application uses the Eclipse Mita framework and requires the XDK Workbench for compilation and deployment.
- Make sure you have a working knowledge of the XDK 110 device and Eclipse Mita concepts.




