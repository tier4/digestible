cmake_minimum_required(VERSION 3.14)
project(digestible)

find_package(ament_cmake_auto REQUIRED)
ament_auto_find_build_dependencies()

install(DIRECTORY include/ DESTINATION include)

ament_auto_package()