cmake_minimum_required(VERSION 3.0.0)
project(hello_world)

set(CMAKE_CXX_STANDARD 14)
set (CMAKE_CXX_FLAGS  "${CMAKE_CXX_FLAGS} -g")

add_executable(hello main.cpp)

