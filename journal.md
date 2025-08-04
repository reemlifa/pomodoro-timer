 
i've had this idea swimming around in my head for a bit but haven't done anything to prep for it. 

today i just made a shitty wireframe of what i what the front main side to look like in canva, but i actually have to design it in cad (once I finish hackpad) and make it look useable lol 
will probably do some more research on the parts i may need to make this work and stimulate it in tinkercad! 

right now my thoughts on a bom:
- arduino nano: needs to be tiny so it can fit in the case
- oled display (not sure the size yet, we'll figure that out later)
- 5 tiny push buttons (for each of the options!)
- usb cable (probably going to make the back of the tomato have a hole so that the wire can go through)
- buzzers or vibration motor??? don't know how to use them yet
- breadboard and mtf wires (have a bunch of mtf wires, might need a larger breadboard though)

![pomodoro timer](https://github.com/user-attachments/assets/acbd7387-0cbe-4bc4-9dec-31c233afcfec)

# August 4th: long time no see! made a schematic!!
uhhhh got a little too busy with the internship to finish this for highway. gonna try and work on it for grounded. 

i made a schematic!! heres my current bom
- xiao rp2040
- 5 push buttons
- MOFSET transistor for the motor
- motor
- diode to not kill my motor
- OLED screen 0.96
- a resistor for the motor

<img width="451" height="297" alt="Screenshot 2025-08-04 at 11 07 42 PM" src="https://github.com/user-attachments/assets/c0ac8b1c-f16b-453b-9a59-a0a6c7506f65" />

time to make my pcb :D

**Total time spent: 5h**

# August 5th: updated the schematic, added footprints
i learned there was a whole host of things wrong with my schematic that seem tiny but would've probably ruined something. i was using smd over dip for the xiao (i hate smd) i changed the oled footprint to the one grounded uses, added the footprint for mofset and motors and diodes. 

<img width="618" height="388" alt="Screenshot 2025-08-05 at 12 06 47 AM" src="https://github.com/user-attachments/assets/e9325064-e344-4dd1-88c2-0099af627a4c" />

