# ROS_humble_PX4
```
cd MicroXRCEAgent 
MicroXRCEAgent udp4 -p 8888
```
Open a new terminal in the root of the PX4 Autopilot repo that was installed above.
```
cd PX4-Autopilot
make px4_sitl gz_x500
```
WORKSPACE
```
cd ~/ws_sensor_combined/src/

andrew@eee:~$ cd ~/ws_sensor_combined/
andrew@eee:~/ws_sensor_combined$ source /opt/ros/humble/setup.bash
andrew@eee:~/ws_sensor_combined$ source install/local_setup.bash
andrew@eee:~/ws_sensor_combined$ ros2 launch px4_ros_com sensor_combined_listener.launch.py

```
