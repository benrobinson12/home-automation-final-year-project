# home-automation-final-year-project

The aim of this project is to produce a home automation system using aESP8266 chip and Node-Red with MQTT (publish and subscribe).

This is achieved by control the esp8266 outputs using node-red on a web pages and mobile.

The mobile will be using an app called Blynk connected to node-red.

the communication between the ESP8266 and the Node-RED software is achieved with the MQTT communication protocol.

A raspberry pi is being used as a server to host node-red. Firstly the raspberry pi is running Jessie and has mosquito MQTT installed on it.

The esp8266 chip is a wi-fi chip with output pins, it is being coded via the arduino IDE. multiple libraries have been used in the code. The pubsubclient which supports MQTT to allow communication to the raspberry pi server. DHT sensor library to allow use of any DHT sensor being used, in this case DHT11.

The chip can now be coded to talk to the server via MQTT and to control the output functions of the device.

The circuit is also required to be built as well as supplied by 5v.