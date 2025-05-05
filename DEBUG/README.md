# CTF-Journey
A journey through CTF 

##  DEBUG   ##

Date: 5th may 2025
Author[s]:
Difficulty : Easy 

## SYNOPSIS ##
Decode serial signal captured during device's booting sequence and find source of inteference

## DESCRIPTION ##

Your team has recovered a satellite dish that was used for transmitting the location of the relic, but it seems to be malfunctioning. There seems to be some interference affecting its connection to the satellite system, but there are no indications of what it could be. Perhaps the debugging interface could provide some insight, but they are unable to decode the serial signal captured during the device's booting sequence. Can you help to decode the signal and find the source of the interference?

## Solution ## 

By opening the given folder . We find .sal file . 
.SAL files ~ Signal Acquisition Log files. 
These files Stores digital signal data and can be opened by SIgrok Pulse view, Logic 2. 

## Logic 2 
This is a software for hardware debugging and logic analyzer. 

Upon Opening the given file through Logic 2 , We View it by ASYNC SERIAL to analyse. 
Debugging it with 115200 Bit rate, 
We find the inteference. 