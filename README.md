pr2_ft_moveit_config
====================

Configuration and launch files for using the PR2 robot with force-torque sensors with the MoveIt Motion Planning Framework

Installation and Running
-----------------------------------

To run this in your PR2, you also need the standard PR2 moveit packages installed (look at the moveit wiki for more details):

    sudo apt-get install ros-<ros_distro>-moveit-pr2

To launch the move group node execute the following command in the terminal:
    
    roslaunch pr2_ft_moveit_config move_group.launch

You can change the URDF used in **demo.launch** by copying your robot's URDF to the **urdf/** folder and changing the **planning_context.launch** launch file.