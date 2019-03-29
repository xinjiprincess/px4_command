# px4_command
Send command to PX4 using Mavros package


# Installation

1. Install the mavros packgae by Binary installation
   
    Please ref to: https://github.com/mavlink/mavros
    
    If you has install the mavros package by source code. Plaese deleat it firstly.
   
2. Create a new ros space called "px4_ws" in your home folder
  
    `mkdir -p ~/px4_ws/src`
  
    `cd ~/px4_ws/src`
  
    `catkin_init_workspace`
  
    `catkin_make`
  
    `source devel/setup.bash`
  
    `echo $ROS_PACKAGE_PATH`

3. Git clone the px4_command package
    
    `cd ~/px4_ws/src`
    
    `git clone https://github.com/potato77/px4_command`
    
    `cd ..`
    
    `catkin_make`
    

# Branch

    fsc_lab branch is used for fsc_lab quadrotor experiment.
