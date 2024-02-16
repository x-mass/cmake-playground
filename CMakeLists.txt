cmake_minimum_required(VERSION 3.10)
project(FinalApplication)

add_subdirectory(LibA)
add_subdirectory(LibB)
add_subdirectory(LibBNew)

add_executable(FinalApplication main.cpp)
target_link_libraries(FinalApplication LibBNew LibA)
# Replace with the next line to observe the difference
# target_link_libraries(FinalApplication LibA LibBNew)

# run with: cmake . && make FinalApplication && ./FinalApplication
