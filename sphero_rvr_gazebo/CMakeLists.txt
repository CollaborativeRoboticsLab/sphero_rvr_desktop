cmake_minimum_required(VERSION 3.16)
project(sphero_rvr_gazebo)
find_package(ament_cmake REQUIRED)

# install gazebo files
install(DIRECTORY
  launch
  worlds
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
