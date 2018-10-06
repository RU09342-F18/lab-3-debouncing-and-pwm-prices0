Author: Shane Price
This code was written through sample code found on online forums that were modified for my needs as well as collaborating with fellow classmates.

Written: Oct 5, 2018

Last Updated: Oct 5, 2018 
# Software Debouncing
This part of the lab involved making debounce code. Debounce occurs when a button is pressed and makes multiple contacts creating multiple pulses in a single press, hence the need for debouncing. This was done on two different boards the MSP430FR2311 and MSP430F5529. This was done by using a timer and flags to stop the button from being used once initially pressed for a determined amount of time, then reenabling it to make another pulse. 

 ## Inputs and Outputs
 ### MSP430F5529
 #### Inputs: P1.1 (Button)
 #### Outputs: P1.0 (LED) 
 ### MSP430FR2311
 #### Inputs: P1.1 (Button)
 #### Outputs: P1.0 (LED) 
