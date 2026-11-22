cmake_minimum_required(VERSION 3.10.0)
project(Custom_Malloc VERSION 0.1.0 LANGUAGES C)

add_executable(Custom_Malloc main.c)

include(CTest)
enable_testing()

