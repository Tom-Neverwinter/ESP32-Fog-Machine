# ESP32 Fog Machine

## Web interface controlable Fog Machine controller
Can be connected to either in SoftAP mode or after being connected to a WiFi Network
Has built in ArtNet Support. Defaults to Artnet Universe 1, address 1
Device uses 2 channels, the first being duration, The second being delay
Device automatically shuts down fog machine heater, and pump if Temperatures go above 300 degrees F or below 0 Degrees F

## Important Pins

- Thermistor is connected to pin A0
- Pump is connected to pin 17
- Heater is connected to pin 33


## WIP

- Web Control of Duration, Delay Variables
- cleaning function with second pump and tubing

- more in parity to "Wled" https://github.com/Aircoookie/WLED
 - Access Point and station mode - automatic failsafe AP
 - 5 user presets to save and load different fog dispersal modes, supports cycling through them.
 - Full OTA software updatability (HTTP + ArduinoOTA), password protectable
 - app for Android and iOS
 - JSON and HTTP request APIs
 - MQTT
 - E1.31
 - UDP realtime
 - Alexa voice control
 - Sync fog of multiple fog machines (UDP notifier)
 - Infrared remotes (24-key RGB, receiver required)
 - Simple timers/schedules (time from NTP, timezones/DST supported)



## Web Interface
 
 Web interface contains 2 pages
 
 Main
 
 
 ![Image description](https://github.com/cpyarger/ESP32-Fog-Machine/blob/master/images/Fog%20Machine%20Info.JPG?raw=true)
 Setup
 ![Image description](https://github.com/cpyarger/ESP32-Fog-Machine/blob/master/images/Fog%20Machine%20Setup.JPG?raw=true)
