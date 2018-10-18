cmake_minimum_required (VERSION 3.8)
project(dive_library)

add_library(dive_library "dive.cpp" "dive.h")
add_executable(dive_exe "main.cpp" "dive.cpp")