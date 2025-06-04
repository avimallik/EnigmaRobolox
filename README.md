# EnigmaRobolox

EngimaRobolox or ARM Robolox is an Android application built for IoT-enabled deployment. This sophisticated application can perform tasks to control home appliances, monitor weather conditions, and read the text-based SMS of a firm alarm from the GSM or CDMA module. </br>

---

## Features

- **Smart Device Control**  
  Control room light, mirror/garage light, and fan using on-screen toggles or voice commands.

- **Speech Recognition**  
  Hands-free automation using Android’s built-in speech recognition (e.g., "room light on").

- **Weather Station Integration**  
  View real-time weather data from a connected weather station (JSON API integration in application) or from a local HTML asset.

- **WebView Dashboard**  
  Access local or remote dashboards for weather and device status within the app.

- **IP Address Configuration**  
  Add, save, and edit the IP address for your IoT server/device dynamically.

- **Voice Command List**  
  See the full list of supported voice commands and instructions.

---
## Useful Links

- **Weather Monitoring Source:**  
[DHT-11 weather monitoring through ESP8266MOD/NodeMCU](https://github.com/avimallik/IoT-Home-weather-monitoring-system-NodeMCU-ESP-8266MOD-Code.git)

- **Home Automation:**  
[Home Automation through ESP8266MOD/NodeMCU](https://github.com/avimallik/NodeMCU-ESP8266MOD-IoT-Automation.git)
---
## How to Use

1. **Clone or download** the project and open it in Android Studio.
2. **Connect** a physical Android device (required for WiFi and speech features).
3. **Build and run** the app.
4. **Set up** your IoT device/server and configure its IP address in the app.
5. **Use toggles or speech commands** to control connected appliances.
6. **Access weather station** data and web dashboards from the app.
7. **(For instructors)** Use the built-in modules to conduct Android development classes.

---

## Supported Voice Commands

- "room light on" / "room light off"
- "garage light on" / "garage light off"
- "fan on" / "fan off"

The app listens for these phrases and sends appropriate commands to your IoT device.

---

## Dependencies

- Android Support Libraries (AppCompat, Design)
- Speech Recognition (built-in)
- Network (WiFi) permissions
- WebView
- SQLite
- HTTPclient
---

## Screenshoots of Actions
![Screenshot_20180919-130700](https://user-images.githubusercontent.com/21225215/219436814-6823dfae-2cdd-4380-8119-53ddf49f7b0e.png)
![Screenshot_20180922-203138](https://user-images.githubusercontent.com/21225215/219436829-0d974020-a6b4-4c57-a46e-235004101966.png)
![Screenshot_20220903-043323](https://user-images.githubusercontent.com/21225215/219436836-156241a5-7fc5-44d9-a549-5ba5d66cf7af.jpg)
![real_data_automation](https://user-images.githubusercontent.com/21225215/219437348-efe56a39-2479-4e17-bec9-3734c7cecc31.jpg)

## Credits

Developed by [Arunav Mallik Avi].  
For any issues or contributions, please open a pull request or issue.

