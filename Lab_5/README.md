# Lab 5A: Eclipse Mosquitto and Eclipse Paho

Subscribing on one terminal and publishing to another:

![image](image1.png)  

Mosquitto status and netstat command

![image](image2.png)  

![image](image3.png)  

Image of both terminals speaking to each other

![image](image4.png)  

Sub.py and Pub.py:

![image](image5.png)  

Sub-multiple.py and Pub-multiple.py:

![image](image6.png)  

Subcpu.py and Pubcpu.py

![image](image7.png)  

For subraspi and pubraspi, I had to change some things around to get this code to work. Firstly the default path was `/opt/vc/bin/vcgencmd`, but I had to change it to `/usr/bin/vcgencmd`, which was the opposite of what was written in the lab. I am on a newer version but the default was for older versions of the Raspberry Pi OS. Secondly, I had to uncomment out this line here: 
`mqttc = mqtt.Client()`, because I got an error saying it did not know what mqttc was. This was done in pubraspi.py and then it was able to connect to the other terminal.

![image](image8.png)  
