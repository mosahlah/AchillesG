# AchillesG
Spherical 2DoF Robot Control System

Arduino program - 
  /partial program
    -Motor controller for stance and locomotion of a spherical robot based on 2 DoF commands articulated through an array of solenoid actuators. Compares orientation with IMU and address of actuators. Sends command to shift registers.
    -Command Console for command menu display and input entry.
    
RaspberryPi program - circuitpython
  /draft only
    -Master controller to command motor controller. Adjusts location data with GPS fedback, communicates to user with bluetooth.
