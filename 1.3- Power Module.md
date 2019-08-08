# Overview

- The module will provide a steady ~5V to Pixhawk and allow the Pixhawk to measure the current and/or voltage of the main battery.
- Depending on the power module you may also have connections to provide backup power and power to supply the servo rail.

- These are the connections with the pixhawk

![power module2](https://user-images.githubusercontent.com/38992224/61215307-c9489700-a70a-11e9-9c32-957ee312896a.jpg)

- This is our power module with the connection to the pixhawk unfortunately removed

![WhatsApp Image 2019-02-10 at 23 04 16](https://user-images.githubusercontent.com/38992224/61215388-0745bb00-a70b-11e9-968b-4015a4208ba3.jpeg)

---------------------------------------------------------------------------------------------------------------------------------------
- To have a detailed description of the power module schematics, please check this link:
    http://ardupilot.org/copter/docs/common-3dr-power-module.html
---------------------------------------------------------------------------------------------------------------------------------------
 # Warnings
                         
- The Power Module provides enough power for the flight controller, receiver, and a few low powered peripherals (lidar, telemetry),
  but does not have enough power for servos or high current devices like FPV transmitters or the RFD900 radios.

 # Common problems
                        
* The 6 pin connector from the power module to the pixhawk is very fragile and you have to deal with it with extreme care.
