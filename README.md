# HumTem_IoT_NodeRed

This mini-project consists of setting up 2 two-way communications architectures that use REST and MQTT protocols.
With ESP32 Wifi module, a DHT11 temperature sensor and an LED.

The objective is to show 2 demos that allow to verify the bidirectional connection:
  - In the upward direction (uplink) go up and display on a graph the temperature and humidity.
  - In the descending direction (downlink) activate an LED from a web interface.

Cloud part: Node Red on a cloud.
Broker locally: Mosquitto
