# EECS 106A Final Project: Autonomous Flying w/Parrot 2.0 Drone

## Linux Installation
In your VM, install:
1. Linux Xenial: https://releases.ubuntu.com/16.04/
2. ROS Kinetic: http://wiki.ros.org/kinetic/Installation/Ubuntu

## Steps after Linux Installation 
1. Run `catkin_make` and `source devel/setup.bash` inside the `eecs106a_final_proj` folder
2. Run `catkin_create_pkg drone_application std_msgs rospy roscpp` and then repeat Step 1 again 
3. `cd` inside the `ardrone_tutorials` folder inside `eecs106a_final_proj/src/` and run `keyboard_controller.py` (you may need to repeat Step 1 if packages are not found)
