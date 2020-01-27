# Gotchi - Online game with Arduino/ESP
* Arduino powered multiplayer game Gotchi based on Tamagotchi

# Available microcontrollers
* <img src="http://tehnopage.ru/_pu/1/28347233.jpg" width="128" height="64">Arduino + Ethernet W5100
* <img src="https://images.ua.prom.st/785300776_w128_h128_wifi-bluetooth-modul.jpg" width="128" height="128"> ESP8266 (NodeMCU, Wemos D1 Mini)
* <img src="http://www.robotop.lv/1802-home/nodemcu-esp-32-v11.jpg" width="128" height="128"> ESP32 (DevKit)

# Hardware requirements
* <img src="https://www.robotop.lv/1174-home/096-128x64-oled-lcd-display-i2c-spi.jpg" width="128" height="128"> 0.96" Inch 128x64 Oled LCD Display
* <img src="https://i.imgur.com/JMdkBTR.png" width="128" height="128"> 3x pushbutton
* <img src="https://cdn10.bigcommerce.com/s-t4yqg98af9/products/631516/images/5559907/apindxecp__57024.1551660674.256.256.jpg?c=2" width="128" height="128"> Router/AP for remote connnection to game server

# Instructions
* Each player must be registered to webpage of game
* Webpage will generate its source code for microcontroller, schematics that user will upload to board and wire pushbuttons, display properly
* Program for microcontroller will download stats, etc, game....
* After user make something (action), it will be sent to webserver, when it will be saved, also players will be ranked based on their activity, actions, experiences, etc.
