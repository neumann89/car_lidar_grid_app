cmake_minimum_required(VERSION 2.8.3)
project(car_lidar_grid)

find_package(catkin REQUIRED rosjava_build_tools)
####find_package(catkin REQUIRED uploadArchives)

catkin_android_setup(wrapper assemble uploadArchives)

catkin_package()

