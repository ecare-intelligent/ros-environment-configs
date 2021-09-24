# ROS Unity Package Patch

Prerequirements: `wstool`

Patch Apply to: `.rosinstall`

Install package

    wstool merge -t src https://raw.githubusercontent.com/ecare-intelligent/ros-environment-configs/master/ros-melodic-desktop-full/ros_unity/ros_unity.patch.rosinstall

Package will be add

Id | pakcage name | Repo Link | depends by
--- | --- | ---| ---
1 | rosbridge_suite | https://github.com/RobotWebTools/rosbridge_suite |
2 | ros_controllers | https://github.com/ros-controls/ros_controllers |