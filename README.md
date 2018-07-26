# castlehomeassistant

This is my home automation configuration and detailing repository.

I still need to configure !secret for sensitive information, so for the time being, this is a cloned version of my configuration pages.

My [Home Assistant](https://home-assistant.io/) installation is running on my server, Castle, which is a custom-built machine running OS X.  At the moment, it is a striking balance between power and efficiency on what could be considered consumer / gamer hardware.

***Castle Specs***

* Intel i7-3700k
* 16gb DDR3 @ 1600mhz
* Gigabyte Ivy Bridge Motherboard (OS X compatible chipset)
* 2x 128gb ssd in OS X software RAID
* 4x WD Red 8TB (shucked from WD USB 3.0 Drives, see /r/datahoarders :) )
* Silverstone GD06 (admittedly tough to house many HDD's in here, but it works!)

## What Castle Runs:

* [Homebridge](https://github.com/home-assistant/homebridge-homeassistant)
* [Plex Media Server](https://www.plex.tv/)
* [OS X Server](https://www.apple.com/macos/server/)
* [Ubiquiti Unifi Controller](https://unifi-sdn.ubnt.com) 
* A print server for an ex-UPS Zebra LP2844 4x6 Label Printer
* [Let's Encrypt](https://letsencrypt.org) : Free, Open, Automated SSL/TLS Certificate Authority Service

## In the future I hope to:

* Implement real version control by not just cloning my current config with redactions and implementing !secret (In Progress)
* Add more lighting controls and automation based on movement/presence
* Build/create inobtrusive "status lights" for security, weather, etc (In Progress)
* Migrate to different hardware, potentially a real server build
* Implement [Pi-Hole](https://pi-hole.net/) and its component for HA: [Sensor](https://home-assistant.io/components/sensor.pi_hole/)
* Switch to Docker
* [Abode home security](https://home-assistant.io/components/alarm_control_panel.abode/)

## Hardware used in my setup:
  
  * Networking
    * Google GFRG Fiber Converter
    * Ubiquiti Edgerouter X    
    * Ubiquiti Unifi 802.11ac AP Lite
    * Cisco SG300-20 Managed PoE Switch
    * Various switches throughout the home
  * Home Control Infrastructure
    * Wink Hub Ver 1 (I, as of yet, have been too cheap to pick up a Lutron Caseta Hub Pro, but my wink hub facilitates communication with the Caseta dimmers and the Wink Relay)
    * Broadlink RM PRo - 433mhz / RF / Infrared transmitter & receiver.  Works great with cheapo 433mhz plugs, my rf-controlled projector screen, and IR home theater components alike.
    * Apple TV 4 - Necessary for for Apple HomeKit offsite access and automation

  * Lights and Switches
    * Lutron Caseta
    * Lutron IR Wireless Dimmer
    * Wink Relay (two gang on/off switch and dashboard that was purchased as a Cyber Monday closeout deal)
    * esp8266 Plugs running Tasmota
    * Sonoff Original inside a Lamp
    
  * Security & Presence Detection
    * iOS Presence Detection
    * XaioMi Aqara Motion & Sensors
    * XaioMi Aqara Door/Window Sensors
 
    
  * Media
    * [Plex](https://www.plex.tv/) The glue that binds all media together
    * Apple TV 4
    * Apple Airport Express - Four zones additional to the Home Theater, not particularly integrated into my HA setup, but useful for music in the kitchen, dining room, and shower.
    * Pioneer Connected HTR
    * Epson HT Projector
    * FAVI drop
    * Google Chromecast 2, Audio
    * Amazon Fire TV Stick
 
