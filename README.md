# ESP8266 WiFi Captive Portal

## Disclaimer
This project is for testing and educational purposes. Use it only against your own networks and devices. I don't take any responsibility for what you do with this program.

## About this project
WiFi captive portal for the NodeMCU (ESP8266 Module) with DNS spoofing.

The built-in LED will blink 5 times when a password is posted.

<b>Warning!</b> Your saved passwords will **not** disappear when you restart/power off the ESP8266.

<b>Note:</b> If you want to see the stored passwords go to "**172.0.0.1**<a>/pass</a>". For changing the SSID, go to "**172.0.0.1**<a>/ssid</a>"

<b>V. 2.0 (Fake sign in)</b>: https://github.com/125K/ESP8266_WiFi_Captive_Portal_2.0



# Installation (Arduino IDE)

1. Open your <a href="https://www.arduino.cc/en/main/software">Arduino IDE</a> and go to "File -> Preferences -> Boards Manager URLs" and paste the following link:
``http://arduino.esp8266.com/stable/package_esp8266com_index.json``
2. Go to "Tools -> Board -> Boards Manager", search "esp8266" and install esp8266
3. Go to "Tools -> Board" and select you board"
4. Download and open the sketch "<a href="https://github.com/125K/ESP8266_WiFi_Captive_Portal/blob/master/WiFi_Captive_Portal.ino"><b>WiFi_Captive_Portal.ino</b></a>"
5. You can optionally change some parameters like the SSID name and texts of the page like title, subtitle, text body...
6. Upload the code into your board.
7. You are done!


## Check out my other projects

- **WiFi-Spam**: :email::satellite: Spam thousands of WiFi access points with custom SSIDs.
  - https://github.com/125K/WiFi-Spam
- **PwrDeauther**: :zap: Deauth a specific WiFi access point or an entire channel.
  - https://github.com/125K/PwrDeauther
