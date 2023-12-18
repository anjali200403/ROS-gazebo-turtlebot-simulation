# ROS-gazebo-turtlebot-simulation

In this repository an explaination pdf is given to explain the steps that need to be followed to build the environment and move turtlebot3 from the start. 

If you want to skip the process you can just clone this repository and run the following commands :
catkin_make

### source devel/setup.bash

### export TURTLEBOT3_MODEL=burger

### roslaunch turtlebot3_gazebo room_setup.launch

Now, to run the turtlebot3 using the keyboard run the following command 
in a new terminal:

### roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
