cmake_minimum_required(VERSION 3.14)
project(digestible)

find_package(autoware_cmake REQUIRED)
autoware_package()

install(DIRECTORY include/ DESTINATION include)

ament_auto_package()