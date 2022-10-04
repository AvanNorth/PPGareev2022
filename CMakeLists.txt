cmake_minimum_required(VERSION 3.23)
project(pp2)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -fopenmp")

add_executable(pp2 main.cpp)

