# Smart-Irrigation-system-using-IOT

This is a repo containing the bluprint and code file of our tinkering Lab project.

Project :

The IOT based Smart irrigation system will automate the irrigation process​ and work according to the soil moisture content and climatic conditions. It will mainly rely on different sensors which will collect the data from there surrounding and then do the controlling of the irrigation mechanism accordingly. All of which can be monitored through a dedicated web page accessible through the farmers smartphone.

The controller in this case is an Arduino board. This Arduino board is connected to the internet platform through ESP8266 module. The user can then command the Arduino through the webpage to start the irrigation motor, after which the complete task of irrigation will be done by the microcontroller automatically. It will continuously read the moisture from the soil through soil moisture sensor and when the moisture level from soil crosses a particular threshold it will turn of the motor thus preventing excess water supply to the crop. This threshold level can be tuned by the farmer according to the needs of the particular crops present in the farm.  

In addition to the soil moisture sensors there is also a rain sensor attached to the board which will help us keep an eye on weather conditions. If it starts raining the motor will be shut down automatically till the rain stops and then it will check if the moisture hasn't reached the threshold value, if so the motor will start again. 
This will optimise the need of water particularly during the rainy seasons. It will also prevent any possible damage to the expensive motors due to rain such as short circuits. In case of power failure, the motor will start as soon as power supply is resumed.  This will control the water usage during irrigation, thus preventing water wastage and also help in increasing yield. Along with these it will also prevent long term damages to soil caused due to excess of water supply.
And most importantly it will reduce the efforts required from the farmers.
