cmake_minimum_required(VERSION 3.8)
project(cs3358_abm_assignment5p1)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Assign05P1.cpp
        llcpImp.cpp
        llcpInt.h)

add_executable(cs3358_abm_assignment5p1 ${SOURCE_FILES})