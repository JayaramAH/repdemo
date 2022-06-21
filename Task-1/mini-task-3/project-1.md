# PROGRAMMABLE REMOTE CONTROL WITH TOUCH SCREEN
## problem statement
Designing a all in all remote control which controls everything we program it to control
## Ideation and Programming
understanding the remotes mechanism
* take the usual remote and record the signal for each button / store it in a sd card / make a touch screen interface with buttons to select the button they need/ replicate the signal using a ir led 
* Part of the pipeline o break

| Part of pipeline  | Feasibility | Advantages | Disadvantages |
|----|----|----|----|
| take the usual remote and record the signal for each button | its easy to just take the remote and press the button and record it,but takes long time|  people can easily select the important buttons the use in regular basis and record it  |  it takes more time for more button |  
| store it in a sd card | it is tough to store all the frequency values in microcontroller we are using, so it is feasible to use a sd card to store the values | we can store as many buttons as we wish | sd card and sd card holder may take a little bit much cost |
| make a touch screen interface with buttons to select the button they need | it is tough to programme a touch screen display, but still it is doable | it will make the users more comfortable with the remote and easier | it is tough to programme |
| replicate the signal using a ir led | it is easy to program a ir led to glow a pwm signal of given frequency | this is the core part of the project, it will send the signal to the reciever | no disadvantages |
## choosing a pipeline
from the above we can start working on the sd card part or touch screen interface part 
  
  _SD card_ : we can customize the size of the sd card and how much to store, we need a sd card module to connect it with arduino/ any microcontroller we are using
 
 _touch screen interface_ : we can use 2.5 or 3.5 inches lcd touch screen display, we can customise thee interface for the users to type the name of the button they want to save the frequency of the remote signal . and the list of the frequently used buttons for them to acceess it quickly.

now we need a draft of the required components ; get them and start the prototyping process
## prototyping phase
it is the part were we make the remote, we have to make several tests and debug the problems which arise , sometimes we might get to go back few steps and make changes and repeat the prototyping process.
