# ATtiny85-Continuity-Tester

The lack of good quality Continuity Testers is shocking.  Even some of the more expensives ones are terrible. 
False Alarms and the potential of damaging sensitive equipment have to be looked at as well. 

I found this ATtiny Continuity Tester schematic from https://github.com/technoblogy/continuity-tester 
Having an easy to assembly kit for DIYers was also considered in the creation of this PCB. 

![image](https://user-images.githubusercontent.com/70423454/217919789-0500e393-519f-4697-af82-e0ebe267925b.png) 

ATtiny85 Program Code can be found here:  http://www.technoblogy.com/list?1ZNS 

It is set to go into sleep mode after 1 minute to save battery power. 
in Sleep Mode, the LED will be powered off and will wake again when the leads touch. 
A power switch was also included so that it can be stored for longer periods of time. 

Not wanting to replace batteries often, I included a dual 18650 holder that has both batteries in parallel. 
The 18650 Batteries will literally self-discharge before being used up by this circuit. 

Project is completely open source with Kicad files to be provided.  This can be modified to your hears desire. 
