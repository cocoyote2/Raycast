cmake_minimum_required(VERSION 4.0)
project(Raycast)

find_package(glfw3 REQUIRED)
find_package(glad REQUIRED)

set(CMAKE_CXX_STANDARD 20)

add_executable(Raycast main.cpp)

target_link_libraries(Raycast PRIVATE glfw glad::glad)