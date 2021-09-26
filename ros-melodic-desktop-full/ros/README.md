# ROS 1 Melodic Package Patch

Prerequirements: `wstool`

Patch Apply to: `melodic-desktop-full.rosinstall`

Install package


    mv melodic-desktop-full.rosinstall .rosinstall
    wstool merge https://raw.githubusercontent.com/ecare-intelligent/ros-environment-configs/master/ros-melodic-desktop-full/ros/melodic-desktop-full.patch.rosinstall
    mv .rosinstall melodic-desktop-full.rosinstall

Package will be add

Id | pakcage name | Repo Link | depends by | depends on
--- | --- | ---| ---
1 | rosparam_shortcuts | https://github.com/PickNikRobotics/rosparam_shortcuts | Moveit |
2 | eigenpy | https://github.com/stack-of-tasks/eigenpy | Moveit |
3 | ompl | https://github.com/ompl/ompl | Moveit |
4 | warehouse_ros | https://github.com/ros-planning/warehouse_ros | Moveit |
5 | pybind11_catkin | https://github.com/ipab-slmc/pybind11_catkin | Moveit |
6 | srdfdom | https://github.com/ros-planning/srdfdom | Moveit |
7 | octomap_msgs | https://github.com/OctoMap/octomap_msgs | Moveit |
8 | object_recognition_msgs | https://github.com/wg-perception/object_recognition_msgs | Moveit |
9 | random_numbers | https://github.com/ros-planning/random_numbers | Moveit |
10 | graph_msgs | https://github.com/PickNikRobotics/graph_msgs | Moveit |
11 | eigen_stl_containers | https://github.com/ros/eigen_stl_containers | Moveit |
12 | ros_control/combined_robot_hw | https://github.com/ros-controls/ros_control | Franka_ROS |
13 | ros_control/rqt_controller_manager | https://github.com/ros-controls/ros_control | Franka_ROS |
