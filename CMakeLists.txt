cmake_minimum_required(VERSION 3.29)
project(untitled18)

set(CMAKE_CXX_STANDARD 20)
FIND_PACKAGE(Boost 1.40 COMPONENTS program_options REQUIRED)
add_executable(untitled18 main.cpp)
TARGET_LINK_LIBRARIES(untitled18 Boost::program_options)
