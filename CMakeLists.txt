cmake_minimum_required(VERSION 3.17)

project(phnt)

add_library(${PROJECT_NAME} STATIC
    src/blank.c
    )

target_include_directories(${PROJECT_NAME} PUBLIC include)