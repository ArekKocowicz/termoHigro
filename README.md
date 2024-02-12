# Themperature and humidity logger
This is code running on my raspberry pi zero with a DHT22 sensor. It reads temperature, humidity, battery voltage and current consumption and sends it to thingspeak channel every minute.
The DHT22 is supplied from raspberry and connected to the pin 4.
There is a 1k resistor between pins 1 (VCC) and 2 (DATA) of the sensor.
There is also a waveshare UPS hat connected. Comunication with UPS uses I2C which must be enabled using <code>raspi-config</code>
