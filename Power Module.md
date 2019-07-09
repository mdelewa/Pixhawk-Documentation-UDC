# Overview

- The module will provide a steady ~5V to Pixhawk and allow the Pixhawk to measure the current and/or voltage of the main battery.
- Depending on the power module you may also have connections to provide backup power and power to supply the servo rail.
---------------------------------------------------------------------------------------------------------------------------------------
- To have a detailed description of the power module schematics, please check this link:
    http://ardupilot.org/copter/docs/common-3dr-power-module.html
---------------------------------------------------------------------------------------------------------------------------------------
 # Warnings
                         
- The Power Module provides enough power for the flight controller, receiver, and a few low powered peripherals (lidar, telemetry),
  but does not have enough power for servos or high current devices like FPV transmitters or the RFD900 radios.

 # Common problems
                        
* The 6 pin connector from the power module to the pixhawk is very fragile and you have to deal with it with extreme care.
