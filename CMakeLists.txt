cmake_minimum_required(VERSION 2.8.3)
project(picknik_ur5_moveit_config)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY launch DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
  PATTERN "setup_assistant.launch" EXCLUDE)
install(DIRECTORY config DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
install(DIRECTORY urdf DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
