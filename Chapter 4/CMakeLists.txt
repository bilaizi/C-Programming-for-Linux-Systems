cmake_minimum_required(VERSION 3.22)
project(Chapter04)
set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_COMPILER g++)
set(CMAKE_CXX_FLAGS "-std=c++23 -Wall -Wextra -Werror -Wpedantic")
set(CMAKE_VERBOSE_MAKEFILE on)

add_executable(init init.cpp)
add_executable(init2 init2.cpp)
add_executable(lambdas lambdas.cpp)
add_executable(mean_value mean_value.cpp)
add_executable(sizeof sizeof.cpp)
add_executable(storage_duration storage_duration.cpp)

