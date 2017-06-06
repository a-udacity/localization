cmake_minimum_required(VERSION 3.7)
project(localization)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp help_functions.h measurement_package.h map.h bayesianFilter.cpp bayesianFilter.h)
add_executable(localization ${SOURCE_FILES})