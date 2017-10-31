# micro-bit_kitybot
4 legged walking robot for BBC micro:bit 
Requires the Kitronik 16 servo driver board (https://www.kitronik.co.uk/5612) and 12 mini servos (https://www.kitronik.co.uk/2565)
Uses the Kitronik servo board package: 
https://github.com/KitronikLtd/pxt-kitronik-I2C-16-servo

The mechanical .stl files are from this hackster.io project: https://www.hackster.io/StaffanEk/kittybot-f21cc0
Included here in the mechanical directory. 

My servos are wired:
1 	Rear Right Hip
2	Rear Right Knee
3	Rear Right Ankle
4 	Not connected
5 	Front Right Hip
6	Front Right Knee
7	Fron Right Ankle
8	Not connected
9	Front Left Hip
10	Front Left Knee
11	Front Left Ankle
12  Not connected
13	Rear Left Hip
14	Rear Left Knee
15	Rear Left Ankle
16  Not connected

Because of the limitations in Makecode (https://makecode.microbit.org/) - integer maths and no trig functions all the servo moves are precomputed.

license CC BY-SA 4.0 https://creativecommons.org/licenses/by-sa/4.0/