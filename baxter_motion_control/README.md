# baxter_motion_control 
Control the motion of the baxter's left arm and move it to the desired position. 

1. Run the baxter shell script with sim specified <br/>
	./baxter.sh sim

2. launch the gazebo simulator <br/>
	roslaunch baxter_gazebo baxter_world.launch

3. Run the python code <br/>
	rosrun baxter_motion_control joint_position_control.py

