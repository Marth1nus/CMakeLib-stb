cmake_minimum_required(VERSION 3.29.0)
project(stb VERSION 0.1.0 LANGUAGES C)

add_library(${PROJECT_NAME} STATIC ./stb_image.c)
target_include_directories(${PROJECT_NAME} PUBLIC .)