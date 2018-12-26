# simGAbSR
GA-based Self Reconfiguration of Modular Robots (Impulse Actuated)

This code is developed in the AI &amp; Robotics Lab of UET Lahore, Pakistan. One can access  the lab-page at http://uet.edu.pk/pp/mct/~aliraza/lab.html  The initial version of the code was written by Haseeb Ahmad under the supervision of  Dr. Ali Raza, towards his Masters thesis. Unfortunately, soon after Haseeb's graduation,  he died due to sudden heart failure. May his soul rest in peace.  The code was further upgraded and augmented by Faiza Munir. The code is provided as open source, E&amp;OE. 

------------------------------------------------------------------------------------------
Any observations and improvements can be directed to (ali.raza at ymail.com)

------------------------------------------------------------------------------------------
Instructions to run the simulator:

1. First of all, Install VRML Editor in MATLAB (if not installed already!). 
Command for the installation of Editor is:

>>vrinstall -install 
or 
>>vrinstall('-install')

In order to check whether Editor is already installed or not, type:

>>vrinstall

2. Run the file startup_simulator.

3. Next, Target Configuration Window will appear, Define the Target Configuration here
by clicking in the required boxes. Clicking anywhere other than the boxes (but not out
of the figure window) will terminate the robot-configuration.
(One can also automate this process by providing the matrix of target configuration)

4. Next, a window will appear for initial configuration. Define the initial configuration 
of the modules robots here similar to step 3.
(One can also automate this process by providing the matrix of initial configuration)

5. Next window will display all the transitions of Robots, Fitness Trend and Algorithm-
Time, etc.

6. You can change the Arena Size by Changing the following number in the  startup_simulator
nosquare=08; % Arena Size definition

-------------------------------------------------------------------------------------------
