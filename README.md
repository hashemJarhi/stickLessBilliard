# stickLessBilliard

in this project, we made a game that is billiard without a sticks.

we used quartus a software tool development, and wrote it with system verilog language,we had an FPGA with inputs, we connected the pins from the FPGA to the software by TCL scripts that each input from FPGA indicates to specific input in the software and we used those input in our implementation so each key (input) on the FPGA send appropiate signal and then we handled the signal in the code we wrote in quratus, then we applied the modules on the FPGA

we used bitmaps to draw the balls on the screen.

we made the user capable of controlling the white ball which he can to indicates where to move and control the ball speed,
and his goal was to hit the white ball towards the other balls and get the other balls into the black holes so he can scores points and win.

the user was directing the ball and giving it power to gain speed through the keyboard that was connected to our software and it was sending signals to white ball module so we handle the signals based on the given input, and we had to make sure that the real physics apply on the balls during the collision like conservation of momentum and conservation of energy.

we measured the side of collision with help of bitmaps and with the given speed we applied the physics law to give the other balls the requried speed and the right direction, and we had to make sure of working well of the other collisions between the rest of the balls if happened so.

we also put a random target that pops up on the screen which indicate which hole you get a bonus if you make the ball fall into it. that target keep change randomly after every hit or every move the player makes.
