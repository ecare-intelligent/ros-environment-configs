# Moveit Package Patch

Prerequirements: `wstool`

Patch Apply to: `.rosinstall`

Install package


    wstool merge -t src https://raw.githubusercontent.com/ecare-intelligent/ros-environment-configs/master/ros-melodic-desktop-full/moveit/moviit.patch.rosinstall

Package will be add

Id | pakcage name | Repo Link | depends on
--- | --- | ---| ---
1 | franka_ros/franka_description | https://github.com/frankaemika/franka_ros | 

Notes

* `franka_ros/franka_description` Version should not be update upper than 0.7.1 due to they removed `robots/panda_arm.urdf.xacro`