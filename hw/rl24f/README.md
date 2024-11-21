## Usage
Open a first terminal and run:
```
$ ros2 launch iiwa_bringup iiwa.launch.py command_interface:="effort" robot_controller:="effort_controller" use_sim:=true
```

in a second terminal run:
```
$ ros2 run ros2_kdl_package ros2_kdl_node --ros-args -p cmd_interface:=effort
```
in this case the robot will be launched with the effort interface

