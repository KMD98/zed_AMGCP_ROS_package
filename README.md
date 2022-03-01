# Information
  - This repo is only meant to direct you to three other repositories that will comprise the ROS network that runs zed with an autonomous 4WD UGV.
# ZED catkin package
  - Go to this repository and git clone the zed_ros_wrapper into your catkin_ws src folder https://github.com/stereolabs/zed-ros-wrapper
# AMGCP catkin package
  - Go to this repository and git clone the ros_essentials_cpp into your catkin_ws src folder (same place as zed_ros_wrapper and zed_ros_interface)  https://github.com/KMD98/ROSMelodicPackage/tree/main/ros_essentials_cpp
  - Please note that this package is currently just a skeleton. Once all of the UGV nodes are developed, this message will be updated and the package will be ready.
  - Currently, the package is under construction. The repo can be used to write all python and c++ codes that do not involve zed dependencies.
  - custom msg for the AMGCP UGV can be found in https://github.com/KMD98/AMGCP/tree/main/ROS_network msg folder
  - UGV codes can be found in PCTesting2.0 folder of https://github.com/KMD98/AMGCP/tree/main/ROS_network
# ZED interface catkin package
  - Go to this repository and git clone the zed_ros_interface into your catkin_Ws src folder https://github.com/stereolabs/zed-ros-interfaces/tree/main
