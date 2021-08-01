# TASK2-MAP
## map by Turtlebot3
* i go to http://turtlebot3.robotis.com/ 
* i entered the PCsetup from Quick Start Guide and i run all the code in that page then from the simulation 
* i run all the code in Gazebo Simulation and SLAM Simulation i faced a problem 
* when i tried to Launch Simulation World the simulation window closed for no reason so i solved this problem by using this code:
~~~python
$ export SVGA_VGPU10=0
~~~ 
* then i retry to open the simulation and finally it opened correctly last thing is that i complete the map by moving the robot using the following keystrokes w s a d and then i save the map, that's it.
