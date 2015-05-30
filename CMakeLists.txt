cmake_minimum_required(VERSION 3.2)
project(recognise)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(recognise ${SOURCE_FILES})