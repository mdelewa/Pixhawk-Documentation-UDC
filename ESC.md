# Types of ESCs
 1- Programmable   
  
 
 2- Has BEC    
   stands for Battery Eliminator Circuit which means you don't need an external battery to power the receiver or other electronics. you can check the output BEC volt by connecting the LiPo battery say 3S (11.1 v) and use voltmeter at the signal wire from the ESC to check it is compatible with the other boards and electronics.   
   more info in this video: https://www.youtube.com/watch?v=kxm6In0SzPE

# Using Programmable ESC
 the ESC we used was Hacker X30 pro it comes with a USB interface that help to connect the ESC through the signal wire to the PC. The drivers of the ESC work on windows xp so we intalled Oracle virtual machine and installed Win Xp. When you reach the program you have full control on the ESC you can change any function but for us we used the default settings.
 
## Troubleshooting
   sometimes we face problems in the whole system of the quadcopter and we want to examine the ESC. You will need a working motor, small charged Lipo battery, Reciever and if the ESC has no BEC use a 5 volt lithium battery. 
#### Steps
   1- Connect the ESC signal wire with the Receiver.
   
   2- Connect the three connectors of the ESC with the motor where the middles are connected together.
        
        warning: Don't use a propeller with the motor in this test unless fixing the motor in a stable arm and taking needed precautions 
   
   3- Power on the Remote (plug the small lithium battery if required).
        
        warning: Make sure that the throttle stick at low.
   
   4- Plug the ESC power connectors in the battery.
   
   5- you should hear beep sounds, when finished raise the throttle stick slightly and watch the motor response.
   
#### Observations
  - If the motor not reaching its max speed it is ESC program made to low.   
  **Solution:** Open the ESC program from the laptop and set the speed to high or normal.   
    Check that it is not a remote signal problem or the remote has trims.
  - 
  
  
# Safety
1- Never power on the ESC without checking on the connectors isolation the three connectors with the motor and the two connectors powering the ESC.   
2- If you felt that the ESC is too hot DO NOT use it.  
  
  
 