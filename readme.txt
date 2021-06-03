For the auto simulation thing, 
the only thing you need to do is to run the code passing the name of the files in the files list in the source code 

files= [........]
 
this is going to be done in both the main/auto_simulate.py  and filldatafile.py that creates excel sheet on your behalf.



The cell library directory contains all the cells implemented along with their layouts. 
the dotspi_files directory contains all the .spi files resulted from the simulation. 
the Simulationlogs directory contains all the text files containing the timing resutls from different combination of Cload and Time


We assumed Cinv to be 100 fF for convenience 

We used the scmos_model.txt provided, not the one on Blackboard. Kp=2.44



