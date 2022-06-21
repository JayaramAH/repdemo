# PROGRAMMABLE REMOTE CONTROL WITH TOUCH SCREEN
## TroubleShooting
Check the sequence in which it works

__take the usual remote and record the signal for each button -> store it in a sd card -> make a touch screen interface with buttons to select the button they need -> replicate the signal using a ir led__     
so if the circuit dint work, it should be a problem in any of the 3 above

**How to find which part causes error?**

check if the sd card module lights up, touch screen lights up, and try and plot the signal recieved by the ir sensor from the usual remote, check with a phone camera that our ir led in which we send signal works fine or not

With this we can find where the problem is.

## problem is with recording the signal from usual remote 
if you plot the signal we get fromm the ir sensor in the arduino IDE, and we dont get any signal
then our ir sensor might have broken

check properly if the remote correctly points towards the sensor, because even that mistake can cause these type of abnormalities
## Problem is with storing it in sd card
check if it lights up

if not, then it might have broken, or the connection may not be given properly

reconnect it and try again

if it lights up

store a frequency value we get from the usual remote in step 1 and name it after the button name

now take the sd card out and put in your phone or pc and check if it stored properly or not
## problem with the touch screen interfce

**problem with the display**

check if the touch screen is glowing,

if not 
check if the display works, by displaying some text in the screen.

try to serial print the input values for the display

if both works, then the display should work

**problem with the touch screen**

check if the touch works by printing the positions of the places we touch

if it works fine then there is no problem with the touch screen, problem is with the code only

else the touch screen is faulty you will have to change it 

## problem with replicating thesignal with ir led

The good thing with ir leds are that we can see them using our mobile cameras.

check if the led is blinking when the signal is passed to the ir led

if blinking

then the ir led is perfectly fine, problem with the code

if not 

then the led must have gone fuse
## problem with the microcontroller

touch and see the ic if it is hot or normal , if its hot, we might have burnt it, in that case we have to change the ic or in the worst case we have to change the whole microcontroller board.
