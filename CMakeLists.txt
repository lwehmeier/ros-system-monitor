cmake_minimum_required(VERSION 2.8.3)
project(ros_system_monitor)


find_package(catkin REQUIRED COMPONENTS
  rospy
  std_msgs
  diagnostic_msgs
)

catkin_package()
