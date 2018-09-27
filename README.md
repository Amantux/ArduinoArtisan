# ArduinoArtisan
An implementation of Artisan Roast Software for a roaster controlled by an arduino


This system will run on an Arduino Due to monitor & Control a fluid bed roaster!


Project goals:
Create a relatively low cost, recirculating fluid bed roaster

Def of Variables:

Temperature Sensors:

float BeanTarget = 0; //Defines the target value of the Coffee Beans in C 
float AirIntakeTemp = 0; //Degree of ambient air near secondary air intake C
float AirRecTemp = 0; //Recirculating air temp, post fan, but pre heater stage
float AirPreChamberTemp = 0; //Post heating element, pre chamber air temperature
float AirPostChamberTemp = 0; //Post heating element, post chamber air temperature
float AirBeanTemp = 0; //Combination of all the sensor readings from the temp probe in bean area 

Flow Sensors-TBD
