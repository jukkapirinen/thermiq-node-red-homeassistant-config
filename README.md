# Thermiq - Node-RED - Home Assistant configuration
* Transforms Thermiq serial communication to MQTT message with Node-RED and vice versa
* Home Assistant
  - Entity configuration for Thermiq entities
  - Lovelace dashboard for Thermiq entities
  - Automations to take action on mode selector changes and respectively on MQTT message to change selector

# Requirements
* [ThermIQ USB device](https://www.thermiq.net/hw/) connected to supported heatpump
* Node-RED
* MQTT broker
* Home Assistant for UI
* Json flow works with Custom version of Arduino I2C Orja  https://github.com/jukkapirinen/arduino_i2c_orja/tree/batch-read

# Screenshots
![UI](images/thermiq-mqtt-screenshot.png?raw=true "ThermIQ Lovelace")

![UI](images/node-red-screenshot.png?raw=true "Node-RED")
