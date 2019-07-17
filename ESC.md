# Overview
* ESC stands for electronic speed controller, it's an embedded IC than receives PWM signal from the receiver and accordingly vary the voltage applied to the motor and thus change its speed and RPM.
* Most modern ESC's have what's called a BEC , which stands for a battery elimination circuit, which is a 5V supply from the ESC to power low power avionics.
* Some ESC's are programmable and their firmware can be upgraded and various parameters can be adjusted like brakes, max speed, minimum PWM signals for activation...etc.
* Such ESC's can be connected through a UART to USB interface, more info about this connection is in the telemetry file on this repo.
  

# Using Programmable ESC

 * the ESC we used was Hacker X30 pro it comes with a USB interface that help to connect the ESC through the signal wire to the PC. The drivers of the ESC work on windows Xp only (cp10x UART interface), so we created a virtual machine and installed Win Xp. On installing you can reset the ESC firmware, upgrade it and modify all the available parameters as discussed before.
 
# Troubleshooting
* Trouble shooting the ESC's required a valid test equipment that consists mainly from a working motor, a propeller , a fixing stand for the motor (a frame or a firewall are sufficient) and an external power source for the avionics (recievers and whatnot).
* Some tested troubleshooting technique that we practiced is described as follows:
   
   
    #### Steps
       1- Connect the ESC signal wire with the Receiver.
       
       2- Connect the three connectors of the ESC with the motor where the middles are connected together.
            
            warning: Don't use a propeller with the motor in this test unless fixing the motor in a stable arm and taking needed precautions 
       
       3- Power on the Remote (plug the small lithium battery if required).
            
            warning: Make sure that the throttle stick at low.
       
       4- Plug the ESC power connectors in the battery.
       
       5- you should hear beep sounds, when finished raise the throttle stick slightly and watch the motor response.
   

  
  
# Safety
1. Never power on the ESC without checking on the connectors isolation the three connectors with the motor and the two connectors powering the ESC.   
2. If you felt that the ESC is too hot DO NOT use it. 
3. Make sure the polarity of the power leads is correct
4. Using a motor with a propeller is the best practice as it's the correct way of loading the ESC.

  
# Useful Links

 * https://www.youtube.com/watch?v=kxm6In0SzPE
 * https://oscarliang.com/multimeter-fpv/
