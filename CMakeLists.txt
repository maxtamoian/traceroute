cmake_minimum_required(VERSION 3.22)
project(traceroute)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O3")

add_executable(traceroute main.cpp)
