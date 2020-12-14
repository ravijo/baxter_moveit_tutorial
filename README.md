# baxter_moveit_tutorial
Moveit tutorial for Baxter Robot

## Package Dependencies
1. [baxter_moveit_config](http://wiki.ros.org/baxter_moveit_config)
1. [baxter_common](https://github.com/RethinkRobotics/baxter_common)

*If you are using Baxter robot, package 'baxter_common' should be exisiting already*

## Compilation
1. Make sure to download compelte repository. Use `git clone` or download zip as per convenience
1. Invoke `catkin` tool while inside ros workspace i.e., `catkin_make`

## Steps to run
1. Initialize moveit planner i.e., `roslaunch baxter_moveit_tutorial moveit_init.launch`
1. Run example i.e., `rosrun baxter_moveit_tutorial example.py`

## Issues (or Error Reporting)
Please check [here](https://github.com/ravijo/baxter_moveit_tutorial/issues) and create issues accordingly.
