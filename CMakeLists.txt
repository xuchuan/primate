cmake_minimum_required(VERSION 3.4)
project(primate)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    README.md main.cpp)

add_executable(primate ${SOURCE_FILES})