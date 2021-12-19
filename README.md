# iot_hardware
This is a dumping ground for the IOT Hardware I have deployed


## Zwave

I like Zwave for its range and the use of the 900mhz spectrum. I have found it to be more reliable than Zigbee devices. I am using Home Assistant with ZwaveJS

* GE/Jasco ZW4006 In Wall Motion Sensor + Light Switch
* GE/Jasco ZW4002 3 Speed Fan Controller
* UltraPro ZWave Smart Rocker Light Dimmer
* GE/Jasco 46201 Smart Rocker
* Aeotec NanoMote Quad Zwave Button


## Zigbee

I have Zigbee devices due to cost efficiencies. Some devices work really well like the Sonoff Motion Sensors. Others... not so much. I'm looking at you Aqara motion sensors!

* GE/Jasco 43102 Zigbee In Wall Outlet
* Aqara Zigbee Button
* Aqara Door/Window Contact Sensor
* Aqara Motion Sensor... These have a LUX sensor in them which is all I use these for. I have bought 3 of them and all of them are garbage for motion sensors in high traffic areas
* Sonoff Zigbee Button
* Sonoff Zigbee Motion Sensors. These things are fantastic, haven't seen false positives and they have an awesome range to them
* Aqara Zigbee Temperature Sensors
* Zigbee LED Strip Controllers

## Wifi Purchased Products

I have a handful Wifi products which I have bought and flashed with Tasmota

* Venstar T7900 Smart Thermostat. Integration with Home Assistant was a breeze. Has a Local API (not flashed, local API works fine)
* Shelly 1. (Flashed with Tasmota)
* Gosund Smart Wifi Outlets (Flashed with Tasmota)
* LVWIT Smart Bulbs (Flashed with Tasmota)
* Teckin Smart Plugs (Flashed with Tasmota)
* [Tuya Wifi IR Remote Control Hub](https://www.aliexpress.com/item/10000013119709.html?spm=a2g0s.9042311.0.0.37544c4drBCZSh) (Flashed with Tasmota) 
* IRobot Roomba I8 (from Costco). No need to flash, this thing runs a local MQTT server
* Athom Smart Bulbs (Flashed with Tasmota)
* Teckin Smart Power Switch (Flashed with Tasmota)


## Bluetooth

I have a few Bluetooth Devices which ESP32 devices connect to and scrape

* Inkbird Waterproof 150 FT Bluetooth Meat Thermometer IBT-4XC
* [AM43 BlueTooth Electric Curtain Motor](https://www.aliexpress.com/item/1005002002637759.html?spm=a2g0s.9042311.0.0.37544c4drBCZSh)
* [Xiami Mija Bluetooth Temperature & Humidity Sensors](https://cloudfree.shop/product/xiaomi-mijia-bluetooth-temperature-and-humidity-sensor/)

## Self Built

I use a lot of D1 Minis based on the ESP8266 chips. I have started adopting ESP32 chips slowly

### Sensors used

* HX711 Load Cell Weight Sensors
* AM312 PIR Motion Sensors
* GY302 BH1750 LUX Sensor
* HC-SR04 Distance Measuring Sensor
* 5v DC 8 Channel Solid State Relay
* DHT22 Temperature & Humidity Sensor
* 
