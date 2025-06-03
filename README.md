# ENGR103---Tamagotchi
C++ code for a basic Tamagotchi-inspired game on an Arduino Circuit Playground Express for my ENGR 103 class

Description:
This game turns the circuit board into a little “Tamagotchi” that you must appease in order to keep it alive. Feeding and playing is done through the buttons, and the switch will put it to sleep or awaken it. Hunger and boredom are defined by specific time intervals and show up as a blue color if not appeased in time will cause a health point to be deducted. The endgame occurs if the Tamagotchi’s health falls to 0 and dies. 

Rules: 
If a health point is deducted, you can only get it back through rest.
If Tamagotchi dies, you cannot revive it.

Controls:
When the LEDs on the Tamagotchi become blue, you want to either play, feed, or put the Tamagotchi to sleep. 
PLAY/FEED - Playing is done by pressing the left button (red LEDs) and feeding is the right button (yellow LEDs). 
SLEEP - The Tamagotchi goes to sleep with the switch, and will regain health by 1 point/1 tenth of a second (purple LEDs with a breathing effect). 
SPIN - Change the spin by moving the circuit board around. 
