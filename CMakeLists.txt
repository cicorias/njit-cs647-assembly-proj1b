cmake_minimum_required(VERSION 3.21)
project(test2)

set(CMAKE_CXX_STANDARD 14)
enable_language(ASM-ATT)

add_executable(test2 main.c)
add_executable(test3 hello.s)


