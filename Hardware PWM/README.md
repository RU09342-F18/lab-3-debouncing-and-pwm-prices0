Author: Shane Price

This code was written through sample code found on online forums that were modified for my needs.

Written: Oct 5, 2018

Last Updated: Oct 5, 2018 
# Hardware PWM
This part of the lab involved making pulse with modulation code based off of the hardware of the MSP boards, MSP430FR2311 and MSP430G2553. The code had the LED start at 50% duty cylce and each button press increased it by 10% until it reached 100% and then restarted from 0% duty cycle. For each button press/interrupt the second on board LED would toggle on/off to show that the interrupt did occur since each duty cycle interval is not seen by the eye.

 ## Inputs and Outputs
 ### MSP430G2553
 #### Inputs: P1.3 (Button)
 #### Outputs: P1.6 (LED), P1.0 (LED) 
 ### MSP430FR2311
 #### Inputs: P1.1 (Button)
 #### Outputs: P1.0 (LED), P2.0 (LED) 
