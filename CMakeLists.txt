cmake_minimum_required(VERSION 3.12)
project(my_project)

set(CMAKE_CXX_STANDARD 14)
include_directories(lib)  # Add this line

add_executable(my_project src/main.cpp)