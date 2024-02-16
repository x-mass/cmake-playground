cmake_minimum_required(VERSION 3.10)
project(LibA)

# Assume PackageB is found using find_package in a real scenario
add_library(LibA INTERFACE)
target_include_directories(LibA INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/include)
target_link_libraries(LibA INTERFACE LibB)
