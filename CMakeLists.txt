cmake_minimum_required(VERSION 2.8.3)
project(omni_im_study)

find_package(catkin REQUIRED COMPONENTS omni_im)

catkin_package(
  CATKIN_DEPENDS omni_im
)

install(PROGRAMS
  src/omni_im_study.py
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)
