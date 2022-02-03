cmake_minimum_required(VERSION 3.20)

project(vulkantutorial)

set(CMAKE_CXX_STANDARD 20)

add_executable(vulkantutorial main.cpp)

target_link_libraries(vulkantutorial glfw pthread vulkan)

