cmake_minimum_required(VERSION 3.8)

project("cosc1337")

include_directories(inc)
include_directories(01-question)
include_directories(02-question)
include_directories(03-question)
include_directories(04-question)
include_directories(05-question)

add_subdirectory(01-question)
add_subdirectory(02-question)
add_subdirectory(03-question)
add_subdirectory(04-question)
add_subdirectory(05-question)
add_subdirectory(test-cases)
