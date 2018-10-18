cmake_minimum_required (VERSION 3.8)
project(factorial_library)

add_library(factorial_library "factorial.cpp" "factorial.h")
add_executable(factorial_exe "main.cpp" "factorial.cpp")