cmake_minimum_required(VERSION 3.9)
project(Vlbager)

set(CMAKE_C_STANDARD 11)

add_executable(Vlbager main.c)

add_library(Vlbagerlib STATIC mylibrary.c)

target_link_libraries(Vlbager Vlbagerlib)


