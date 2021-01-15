cmake_minimum_required(VERSION 3.15)
project(cppproj)

set(CMAKE_CXX_STANDARD 14)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LOCAL_JUDGE")

add_executable(cppproj main.cpp)