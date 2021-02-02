This is a bug fix version of https://github.com/CPFL/Autoware/tree/master/ros/src/computing/perception/localization/lib/fast_pcl/ndt_gpu.
# first you should install ros-meldic catkinConifg.cmake
sudo apt-get install ros-melodic-desktop-full
sudo apt-get install ros-melodic-rqt*
sudo apt install ros-melodic-velodyne-pointcloud
# sencond your should update cmake version 3.16.0 to solve the pthread_create error
# third and then update egines version 3.3.90 to solve the math_functions.hpp error 


