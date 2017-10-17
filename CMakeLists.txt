cmake_minimum_required(VERSION 2.8.3)
project(nccr_demo_visualization)

## Find catkin macros and libraries
find_package(catkin REQUIRED
	navigation_rviz_plugins
)

catkin_package(
	CATKIN_DEPENDS
	navigation_rviz_plugins
)
