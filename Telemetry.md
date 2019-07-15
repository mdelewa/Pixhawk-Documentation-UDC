
# Overview

* The Telemetry is an ideal module to set the remote sensing connection module between Flight controller and ground station. It features small volume, cost effective, wider transmission range, and it allows us to do things that other data transmission modules can't do.

* Most commercial telemetries run on either 915 or 433 Mhz, which is the allowed bandwidth according to legal reasons.


# Setup
* Most telemetries run a 5 pin output (Rx - Tx - VCC - GND - RTS/CTS), usually only 4 pins are wired (Cts isn't used unless it's high grade telemetry), and then connected to the flight controller.
* The cables use JST housings and Hiroose DFT housings to connect to the Pixhawk, These housings are also used in both the power module and GPS connections and it's advisable to research them and how to unplug the crimps from them.
* Software configuration might be needed for the telemetry, In such case the USB unit can be easily programmed through the specified software in the manual of the telemetry, as for the other unit there is 2 options:
  1. Using a UART to USB bridge.
  2. Connecting to arduino and bridge it over the existing UART converter.
  
Using the indicated software it can be programmed easily.

* Most of the parameters are explained in the links provided below.
* The antenna can be swapped with a stronger one for more range.

# Common problems

* Usually most of the problems result from bad wiring, and thus all wiring schematics should be revised before turning on the telemetry and always make sure that the wiring on the telemetry side is matching with that on the flight controller side.
* In case of multiple telemetries in one place, the channel used must be changed through the software provided to prevent any interference or signal weakening.


# Useful links

* https://www.geeetech.com/wiki/index.php/3DR_Radio_Telemetry
* http://vps.oborne.me/3drradioconfig.zip
* https://smaccmpilot.org/software/gcs-smaccm-sik.html
* How to use an Arduino as a USB to TTL converter : https://www.youtube.com/watch?v=qqSLwK1DP8Q

* How To Connect & Config 3DR V1 915MHz Telemetry Radio for Pixhawk APM :
https://www.youtube.com/watch?v=ZooogJNdDE4
