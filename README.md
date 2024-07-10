# Human-Fall-detection-system 
Our project makes use of the concept of the Internet of 
Things and inculcates all the essential elements that are 
required by an IoT system. They are: 
• Sensing: To detect a fall, we need the values of 
acceleration and angular orientation of the subject. 
Hence to obtain these values we use the MPU6050 
sensor which is a three-axis accelerometer and 
gyroscope. To have a simultaneous check on health 
as well, we make use of a pulse sensor. Further, a 
GPS sensor is used to find the location of the device. 
• Processing: For the task of processing, we make use 
of the NodeMCU ESP8266 module which executes 
our main logic of fall detection. We preferred it over 
Arduino because ESP8266 also provides WiFi 
connectivity for communication. Here also comes 
the role of edge computing in our project. 
• Actuation: There’s a buzzer which beeps once a fall 
is detected, to alert the surroundings. Virtually, an 
alert message is generated on fall detection which 
may also be considered as an actuator. 
2
• Connectivity: Our NodeMCU helps in connectivity 
too, establishing a WiFi communication over which 
the alert messages are sent to the concerned people. 
Over any other communication technology, WiFi 
has the advantage of enabling long range 
communication and hence makes our device 
portable. 
• Cloud: While the fall detection logic is 
implemented on the edge, the cloud plays the role 
in storing the history of falls and regular pulse data. 
It acts as a link between the client device and the 
devices of the concerned people
