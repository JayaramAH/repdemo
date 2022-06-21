# DIY apple airtag using esp32
## Problem Statement:
Designing a locating system to find the lost things, by with oled display showing the distance of the object 
## Ideation and planning:
understanding the esp32 air tag's mechanism

* UWB(ultra wide band)module / oled display / program to find the distance
* Part of the pipeline to break

| Part Of The Pipeline | Feasibility | Advantages | Disadvantages |
|----|----|----|----|
|UWB(ultra wide band) module | it is feasible to buy the esp 32 board along with UWB module.but it might cost a litte bit around 3000 Rs| the UWB module alows us to find the distance very accurately, even over 10 cm | it cannot cover long range distances |
| oled display | it is easier to buy and program on oled display | we can show the distance of the object in the oled display | oled displays may degrade on exposure to sunlight |
| program to find the distance | it is a little tough to find the distance using the UWB module | it is necessary for this project | no disadvantages|
## Choosing a pipeline
from the above, we can work on UWB part 
UMB: the UMB module can only measure short range distance, and so we cannot use it for long range

we can add up gps module for long range distances like 2-3 metres

## prototyping phase 
This is the phase to create the airtag

And check for mistakes and correct them

We might face a lot of trouble like the precission in distance measurement, we'll have to debug them and continue the process till we get the desired output
