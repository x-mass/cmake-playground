cmake_minimum_required(VERSION 3.10)
project(LibBNew)

add_library(LibBNew INTERFACE)
target_include_directories(LibBNew INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)
