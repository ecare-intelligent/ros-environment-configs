# ROS Unity Package Patch

Prerequirements: `wstool`

Patch Apply to: `.rosinstall`

Install package

    wstool merge -t src https://raw.githubusercontent.com/ecare-intelligent/ros-environment-configs/master/ros-melodic-desktop-full/ros_unity/ros_unity.patch.rosinstall

Package will be add

Id | pakcage name | Repo Link | depends on
--- | --- | ---| ---
1 | ros_controllers | https://github.com/ros-controls/ros_controllers | four_wheel_steering_msgs
2 | four_wheel_steering_msgs | https://github.com/ros-drivers/four_wheel_steering_msgs | urdf_geometry_parser
3 | urdf_geometry_parser | https://github.com/ros-controls/urdf_geometry_parser | 