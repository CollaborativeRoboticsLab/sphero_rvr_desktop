cmake_minimum_required(VERSION 3.16)
project(sphero_rvr_desktop)
find_package(ament_cmake REQUIRED)

# install launch and rviz files
install(DIRECTORY
  launch
  rviz
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
