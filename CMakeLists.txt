cmake_minimum_required(VERSION 3.22)
project(OSLab3)

set(CMAKE_CXX_STANDARD 14)
set(PROJECT_BINARY_DIR .)

add_executable(OSLab3 main.cpp)
add_executable(hacker hacker.cpp)
add_executable(main main.cpp)
add_executable(hook hook.cpp)
