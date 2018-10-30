cmake_minimum_required(VERSION 3.9)
project(8086tiny)

set(CMAKE_CXX_STANDARD 11)
#add_definitions(-DNO_GRAPHICS)
add_executable(8086tiny 8086tiny.c)
target_link_libraries(8086tiny -lSDL2 -lSDL2_image -lSDL2main)
