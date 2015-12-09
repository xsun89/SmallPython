cmake_minimum_required(VERSION 3.3)
project(SmallPython)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES src/main.cpp src/intObject.cpp src/object.cpp src/strObject.cpp)

add_executable(SmallPython ${SOURCE_FILES})