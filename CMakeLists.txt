cmake_minimum_required(VERSION 3.20) 
project(exocross)
add_executable(exocross src/main.cpp)

target_link_directories(exocross PRIVATE lib/)
target_link_libraries(exocross PRIVATE glfw3 opengl32 gdi32 glu32)

include_directories(include/)
