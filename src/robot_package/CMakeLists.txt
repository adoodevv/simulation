cmake_minimum_required(VERSION 3.5)
project(robot_package)

find_package(ament_cmake REQUIRED)
find_package(rclpy REQUIRED)

install(DIRECTORY launch models
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
