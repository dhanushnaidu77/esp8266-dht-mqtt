ESP8266 DHT Sensor MQTT Client

This Arduino script reads temperature and humidity data from a DHT sensor connected to an ESP8266 microcontroller and publishes the readings to an MQTT broker. The script is designed for IoT projects that require remote monitoring of environmental conditions.

Key features:

Wi-Fi Connection: Connects the ESP8266 to a specified Wi-Fi network.
MQTT Communication: Publishes temperature and humidity data to specified MQTT topics.
DHT Sensor Integration: Supports DHT11, DHT22, and DHT21 sensors for temperature and humidity readings.
Automatic Reconnection: Handles reconnection to Wi-Fi and MQTT broker if the connection is lost.
Configurable Interval: Allows setting the interval for publishing sensor data.
