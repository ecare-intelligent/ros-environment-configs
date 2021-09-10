# Moveit Package Patch

Prerequirements: `wstool`

Patch Apply to: `.rosinstall`

install package


    wstool merge -t src https://raw.githubusercontent.com/ecare-intelligent/ros-environment-configs/master/ros-melodic-desktop-full/moveit/moviit.patch.rosinstall

Package will be add

Id | pakcage name | Repo Link | depends by
--- | --- | ---| ---
1 | franka_ros/franka_description | https://github.com/frankaemika/franka_ros | 