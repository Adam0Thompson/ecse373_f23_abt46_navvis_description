# Navvis Description package

## Package Overview
This package contains the setup, and robot description of the navvis robot. When used properly, this package will generate a render of the navvis robot, complete with realistic sensors with positions and orientations matching that of the real life navvis robot.


## Instructions
1. In your terminal, set up the ros environment and pull this package
2. To use this package, the following line should be all you need:
    - roslaunch navvis_description display.launch
3. You can add arguments to this line ot customize the way the package runs
    - use_xacro:= true/false   this will determine if the xacro version of the file is used, or the urdf version is used. 
    - use_joint_state_publisher_gui:= true/false    this will determine if the wheels can be controlled using a ros gui
4. Once this is running, you are all done


## Author Comments
Im unsure of what the intended "file" input is supposed to be, so that was left undone. Furthermore, im not 100% sure of what is meant to be in this README, but i hope what i have written here is sufficient.