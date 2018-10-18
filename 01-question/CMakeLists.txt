cmake_minimum_required (VERSION 3.8)
project(evaluation_library)

add_library(evaluation_library "evaluation.cpp" "evaluation.h")
add_executable(evaluation_exe "main.cpp" "evaluation.cpp")