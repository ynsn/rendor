cmake_minimum_required(VERSION 3.10.3)
project(Rendor)

link_libraries(rendor)
include_directories(../include)

add_executable(triangle triangle.cpp)
add_executable(triangle_shader triangle_shader.cpp)