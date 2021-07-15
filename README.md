# Automated-Room-with-Manaul-Override-using-IR-remote
The project aims to automate the basic appliances of a room like fan and light. The system uses Arduino Uno as its brain and the software simulation of the system has been developed using Tinkercad
The system uses an LM35 temperature sensor to sense the temperature of the room and a Photoresistor to sense the ambient light in the room. The results from both the sensors are fed into Arduino Uno. The  speed of fan is set on the basis of ambient temperature. A minimum and maximum temperature has been set so that the fan turns on only after the temperature is above the minimum temperature and operates at full speed after the temperature crosses maximum speed. The state of light bulb is set using a photoresistor so that the bulb turns on only after it's dark in the room. A 16x2 LCD display is used to display the temperature of the room as well as the speed of fan.
