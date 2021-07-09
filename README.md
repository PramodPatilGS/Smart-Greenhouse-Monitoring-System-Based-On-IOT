# Smart-Greenhouse-Monitoring-System-Based-On-IOT
Greenhouses have to be monitored manually whereas by making it a smart greenhouse that is by using IoT technique it can be monitored from faraway places also. Different sensors as per the requirement are used to monitor greenhouse and perform the actions according to the parameters sensed. The conditions are predefined by the maintainer so that the growth of the plant is not affected by environmental conditions.
## Methodology/Approach
In this project, we are implementing the greenhouse setup using cisco packet tracer. A network is formed by connecting the sensors .Temperature sensor to sense the environment temperature, humidity sensor to check the humidity, soil moisture sensor to detect the amount of water present in soil and CO2 detector to check the concentration of CO2 in air. Solar cell is used as the energy generator in the designed system and a smart door system is implemented to control the access.

Fig1 shows the block diagram of Smart greenhouse based on IoT in Cisco packet tracer. The block diagram contains temperature monitoring system, humidity monitoring system, fire detection system, co2 detection system, smart lighting system, moisture monitoring system, solar energy generator system, smart door system . All the devices are connected using the internet. A smart phone is used to monitor the devices in the greenhouse. Wireless devices are used to implement the designed system.
![image](https://user-images.githubusercontent.com/69564968/125072932-e08fa480-e0d8-11eb-98e3-21b469c3f1de.png)

## SMART PHONE CONFIGARATION
![image](https://user-images.githubusercontent.com/69564968/125073016-02892700-e0d9-11eb-9916-930f4a870cc5.png)
## TEMPERATURE MONITORING SYSTEM:
Temperature monitoring system contains temperature sensors, thermostats, heating elements, and cooling elements. Temperature sensor keeps a check on the temperature of the environment and displays the value on a connected LED or monitor. The temperature sensed by the sensor is converted into appropriate form and is given as input to the Thermostat .Thermostat is used to control temperature in a greenhouse based on the temperature sensed by the temperature sensor. Heater is activated when the temperature falls below the preset value and cooler is activated when the temperature is greater than the preset value. The thermostat is in an off state when the temperature inside the greenhouse is in the acceptable range for the positive growth of plants .

![image](https://user-images.githubusercontent.com/69564968/125073175-32d0c580-e0d9-11eb-8770-6c41db83238d.png)
## HUMIDITY MONITORING SYSTEM:
Humidity monitoring systems contain humidity sensors, humidifiers.
Humidity sensors measure the amount of water (humidity) content present in the air. Humidifier is used to maintain the moisture content in the air. Humidifier is activated when the humidity percentage in the greenhouse falls below the desired value.

![image](https://user-images.githubusercontent.com/69564968/125073278-5562de80-e0d9-11eb-8369-8cb55ae2c7a2.png)
## FIRE SAFETY SYSTEM:
Smoke detection system contains a smoke detector, fire sprinkler, Siren. A smoke detector is a device that senses the presence of smoke .As soon as the fire is detected a message is delivered to the security panel and the fire alarm is activated. When there is any fire emergency, the sprinkler will be activated by itself as soon as the smoke detector detects smoke.

![image](https://user-images.githubusercontent.com/69564968/125073345-6d3a6280-e0d9-11eb-989d-b78279bc36c6.png)
## CO2 DETECTING SYSTEM:
The CO2 detecting system contains a CO2 detector, exhaust fan. Carbon dioxide detector is a device which senses the concentration of carbon dioxide in the atmosphere. There are basically two types of CO2 detectors, IR and chemical sensors. CO2 plays an important role in the growth of plants. It is necessary to maintain the CO2 content in the greenhouse. Hence the C02 sensor is used to monitor the CO2 levels. when CO2 detected in greenhouse is high with respect to desired value exhaust fan is operated at high speed and when CO2 detected with respect to acceptable value is moderate exhaust fan is operated at low speed and when CO2 is within the acceptable the range exhaust fan is turned off.Old car which generates a lot of CO2, CO and contributes to pollution is used to produce CO2 to check for proper working of the designed system.

![image](https://user-images.githubusercontent.com/69564968/125073398-83482300-e0d9-11eb-87fd-1afda3f0b978.png)
## SOIL MOISTURE MONITORING SYSTEM:
Soil moisture monitoring system contains a water level monitor, lawn sprinkler. Water level monitor measures the water content present in soil which is the indication for moisture content in soil. Particular amount of moisture has to be maintained in soil for healthy plant growth. When the moisture content falls below the preset value water sprinkler is activated. 

![image](https://user-images.githubusercontent.com/69564968/125073471-9ce96a80-e0d9-11eb-8bc5-aca7b49ea5cb.png)
## SOLAR CELL:
Solar cell contains a solar panel, power meter, and battery. A solar panel converts sunlight into electricity by using the appropriate technique. The power produced by the solar panel can be known using the power meter (which measures power across the device to which it is connected). The electricity generated by the solar panel is converted and stored in a battery which is connected to all the devices. This project uses solar cells to supply energy for all the devices which is also eco-friendly.In this system we have connected an electric gadget to battery.When battery saves the energy as much as the set value(30%) then electric gadget will get on.

![image](https://user-images.githubusercontent.com/69564968/125073530-bd192980-e0d9-11eb-8d41-ae13e2716504.png)
## SMART DOOR SYSTEM:
Smart door system contains RFID valid card, RFID invalid card and RFID reader. If the RFID reader reads a valid card then the door will unlock and siren is off, else if the motion detector is on and the RFID reader reads it invalid then the door will be locked and the siren will get on.Webcam is also on for all time.  

![image](https://user-images.githubusercontent.com/69564968/125073588-d326ea00-e0d9-11eb-94f2-89c92233fc15.png)
## FLOW CHART:
 The general flow chart of the methodology used in this project. The same procedure is used for all the systems used in this design. First the sensors sense their respective parameters and the values sensed are converted into the appropriate format which are then fed to the actuators. The actuators are activated based on the input given following predefined conditions.
 
 ![image](https://user-images.githubusercontent.com/69564968/125073681-f5206c80-e0d9-11eb-99dd-3665ff6e5684.png)
## Conclusion:
Greenhouses are used a lot nowadays to increase productivity and grow plants in a controlled environment. Making it smarter eases the work of the maintainer as there is no need to monitor the environmental conditions manually.There are many sensors are used to sense and actuators are activated according to the predefined conditions.sensors and devices required to maintain the greenhouse conditions with electricity generation using solar energy, smart lighting and other monitoring systems.





