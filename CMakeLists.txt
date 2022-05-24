cmake_minimum_required(VERSION 3.0)

project(helloSLAM)

add_executable(helloslam main.cpp)

add_library(hello hello.cpp)

add_executable(useHello useHello.cpp)
target_link_libraries(useHello hello)
