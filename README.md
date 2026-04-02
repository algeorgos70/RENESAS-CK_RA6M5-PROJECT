# RENESAS-CK_RA6M5-PROJECT
In the files below you can see a project that i created for my university lecture. 
The project its based on the CK-RA6M5 cloud kit of Renesas, using the on board microphone.
I created a Keyword Spotting with the words Red, Green, Blue and when the system identifies the word lights up the corresponding led on the board.
The platform that I used for training the AI was EDGE IMPULSE, where i created 4 different classes (RED, GREEN, BLUE, Unknown) using the microphone of my laptop and the on board microphone.

CODE
If you open the src/ei_main.cpp you can find the variable ei_run_impulse() its the location where the code runs.

Down below I will add some videos that guided me to create this project.
1st
https://www.youtube.com/watch?v=nkENds3GPNs&list=PL010Y3tdmGvPfGgObR4-xfWfBly_b3-7j&index=9&t=232s
2nd
https://www.youtube.com/watch?v=T6tKej6BTIs&list=PL010Y3tdmGvPfGgObR4-xfWfBly_b3-7j&index=12
