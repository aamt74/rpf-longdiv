cmake_minimum_required(VERSION 3.13)
project(feynman)

set(CMAKE_CXX_STANDARD 17)

find_package(Boost CONFIG)
include_directories(${Boost_INCLUDE_DIRS})

add_executable(feynman feynman.cpp)
