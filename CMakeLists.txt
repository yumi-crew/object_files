cmake_minimum_required(VERSION 3.5)
project(object_files)

find_package(ament_cmake REQUIRED)

install(DIRECTORY stl
        DESTINATION share/${PROJECT_NAME})

ament_package()
