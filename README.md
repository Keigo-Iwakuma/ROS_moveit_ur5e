# ROS_moveit_ur5e
This is repository for the ur5_e_moveit_config fixed to be used with ur_robot_driver in ROS melodic devel.

## ROS package (Driver and Moveit configuration) to move Universal robot 
- Driver (before kinetic devel): [ur_modern_driver](https://github.com/ros-industrial/ur_modern_driver)
- Driver (after melodic devel): [ur_robot_driver](https://github.com/UniversalRobots/Universal_Robots_ROS_Driver)
- Moveit configuration (including e-series): [universal_robot](https://github.com/fmauch/universal_robot/tree/calibration_devel)

The above configuration was written to use with ur_modern_driver. So if you use the config with ur_robot_driver, some points should be fixed.(2nd line in /config/controllers.yaml and the 53rd line in /launch/move_group.launch)

## the way to execute
I will write later.
