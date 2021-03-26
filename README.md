# LTEBS_2021_II_Group_03_EAGLE
Laboratorio di Tecnologie Elettroniche e Biosensori S2021-II Group 03 EAGLE

In the Library folder, inside the Group_03_Library file we have inserted the two additional devices we were required to make and the microcontroller, for which we modified the footprint (setting line width of the silkscreen according to the manufacturer's specs); other devices referred to Sparkfun Library were not included, supposing to be in your possess. 
For what regards the TMUX device, we built the UQFN package, as specified by the description table inside the PDF, even if inside the provided schematic pins followed the 
TSSOP pattern. The same applies for the CY8CKIT059-TARGET: the table said to pick this, whereas inside the schematic the one used was the CY8CKIT059-TARGET_3: as before, we 
followed the table specs.

Inside the .brd file, Power Jack device looks like it exits the pcb: we intentionally placed it there folowing some examples online. 

All traces are of 10 mils, as you asked in the assignment document. However, due to the small dimension of the MUX, the design rules generated errors due to the clearance of the traces connecting the pads to the other pins. To overcome this problem, we decided to convert the width of all the traces connected to the MUX to 8 mils.

We added Silkscreen references for all SMD components, respecting manufacturer's rules of clearance and distance from the pads (8 mil from any exposed copper part).
