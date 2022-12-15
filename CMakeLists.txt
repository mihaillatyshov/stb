cmake_minimum_required(VERSION 3.24)
project(stb VERSION 1.0)

add_library(${PROJECT_NAME} INTERFACE)
target_include_directories(${PROJECT_NAME} INTERFACE .)
