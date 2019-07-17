
# Overview
* The Rc system is the main gateway of controlling the air vehicle, it's the most reliable control system that's immune to most interference problems that you can face on using telemetries and remote connections through 4G connections.
* On using flight controllers like the pixhawk and ardupilot a PPM encoder is used to convert analog PWM signals into digital ones that the controller can interpret.
* Each receiver channel is connected to its equivalent slot in the PPM encoder and then through a single 3 pin cable it's connected to the controller.
* In regular flight, trims and sub trims might be applied but when using a flight controller no trims nor sub trims are applied through the remote ie. no trims on remote !!! 
* Radio calibration must be done on the ground station side to set the limits of the PWM signals sent and received.
* Some radios have the ability to save various configurations for the switches and sticks, refer to the radio manual for more information.
* Each remote must be binded to its corresponding receiver before usage to prevent any interference.
* Some receivers use different types of protocols like S.Bus which might need inversion, Refer to the manual for more information.

# Useful Links
* https://www.youtube.com/watch?v=S5hMZ-hioe4
* https://www.rc-airplane-world.com/radio-control-gear.html
* https://oscarliang.com/uninverted-sbus-smart-port-frsky-receivers/
