# AchillesG
Spherical 2DoF Robot Control System
Arduino program - 
Motor controller for stance and locomotion of a spherical robot based on 2 DoF commands articulated through an array of solenoid actuators. Compares orientation with IUM and address of actuators. Sends command to shift registers.
RaspberryPi program - 
Master controller to command motor controller. Adjusts location data with GPS fedback, communicates to user with bluetooth.
