## CTF Journey ##
A journey through CTF

## JAILBREAK ##

Date : 11 May 2025 
Author[s]:
Difficulty : Very easy 

## SYNOPSIS ##


## DESCRIPION ##


## SOLUTION ##
By opening the given IP address in web, we get a page with "STAT", "INV", "DATA", "MAP", "RADIO", "ROM". 
Pages ~ "STAT", "INV", "DATA", "MAP", "RADIO" tends to show no help with finding flag.txt. 

Under "ROM" , 
Update xml version, XXE payload 
![alt text](image.png)

Upon updating this , we get our flag 
