cmake_minimum_required(VERSION 2.8.3)
project(workcell_scene_description)

find_package(catkin REQUIRED)

catkin_package()

include_directories()

install(DIRECTORY config DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY urdf DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY worlds DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})