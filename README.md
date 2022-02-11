# 2log-dot-hardware

This repository contains the KiCad Project for the 2log Dot. The hardware is designed to be used with [2log Dot](https://github.com/2log-io/2log-dot "2log Dot Firmware")

## Parts

The PCB consists of a 4-Layer stack. All required parts are through hole components with the exception of the capacitor C1 which is a combined footprint.
Besides the PCB itself you need the following parts:
  * 24 Led WS2812B Ring with 4 contacts (diameter 66mm)
  * SMD Capacitor 5mm diameter, about 10uF
  * (alternative) THT Capacitor, about 10uF
  * Wemos D1 mini ESP32 (ESP8266 will not work)
  * PN532 RFID Reader V3 (red modules, sold under elechouse brand or clones)
  * mini pushbutton (the tiny black/silver ones)
  * _(optional) 14 Pin Male and 13 Pin Female 2.54mm Pin Header/Socket for expansion port_
  
## Images

![esp side](https://github.com/2log-io/2log-dot-hardware/blob/main/images/2logDot_1.png "esp side")
![rfid side](https://github.com/2log-io/2log-dot-hardware/blob/main/images/2logDot_2.png "rfid side")
