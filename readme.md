#  使用方法

```bash
# 安装
sudo dpkg -i ros-kinetic-slamoptolidar-ros_1.4.1-0xenial_amd64.deb
# 文件被安装到 /opt/ros/kinetic/share/slamoptolidar_ros
#使用
roslaunch slamoptolidar_ros lidar_view.launch
#如果不出意外，你就可以看到，rviz中的雷达扫描信息。
#如遇意外请给激光雷达重新上电，
#测试
ping 192.168.0.1
#卸载 
sudo dpkg --purge ros-kinetic-slamoptolidar-ros
```

