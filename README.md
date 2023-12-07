# Weather-monitoring-system
This is my first repository. This contains pressure, humidity and temperature detection as IoT project.
Its a team project for semester 5. For Temperature and Humidity DHT11, for pressure BMP180 is used. Initially data is being sent to Arduino by DHT11 and BMP180. Then by SPI(Serial Peripheral Interface) data is sent to NodeMCU in string form. The data is being retrieved in float form in NodeMCU code and is sent to thingspeak.com.   
