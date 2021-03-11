cmake_minimum_required(VERSION 3.0.2)
project(ben_gazebo)

find_package(catkin REQUIRED COMPONENTS
  xacro
  ben_description
  usv_gazebo_plugins
  vrx_gazebo
  wamv_description
  wamv_gazebo
)

catkin_package(
  CATKIN_DEPENDS xacro usv_gazebo_plugins vrx_gazebo
)
