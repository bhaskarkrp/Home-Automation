# Home-Automation
Home automation using esp8266 and blynk_library,google assistant


- Download the Blynk app (App Store, Google Play)
- Get the Auth Token from the app
- Import this library to Arduino IDE. Guide here
- In Arduino IDE, select File -> Examples -> Blynk -> Boards_Ethernet -> Arduino_Ethernet
- Update Auth Token in the sketch and upload it to Arduino
- Connect your Arduino with Ethernet shield to the internet

When you are connected - check the included examples on how to use different types of connections (transports) and explore Blynk features. You can combine any example for your hardware + transport + features.

PS: If you could not find the Board esp8266, do this- GO TO FILE->prefernce->add this URL on bottom in borad manager(http://arduino.esp8266.com/stable/package_esp8266com_index.json) then GO TO TOOLS and search in Board Manager (esp8266) and install.
