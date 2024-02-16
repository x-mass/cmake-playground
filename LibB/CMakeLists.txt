cmake_minimum_required(VERSION 3.10)
project(LibB)

add_library(LibB INTERFACE)
target_include_directories(LibB INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)
