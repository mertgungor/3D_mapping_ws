# How to run

```
roslaunch rslidar_sdk start.launch
rosrun rs_to_velodyne rs_to_velodyne XYZI XYZIRT
rosrun stim300 stim300
rosrun imu_complementary_filter complementary_filter_node 
roslaunch fast_lio mapping_velodyne.launch
```