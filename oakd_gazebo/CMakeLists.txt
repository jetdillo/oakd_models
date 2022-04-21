cmake_minimum_required(VERSION 2.8.3)
project(oakd_gazebo)

find_package(catkin REQUIRED)

catkin_package(
    DEPENDS
        gazebo_ros
        gazebo_ros_control
	stereo_image_proc
)

install(DIRECTORY launch models worlds
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
