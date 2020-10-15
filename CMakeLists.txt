cmake_minimum_required(VERSION 3.17)
project(NetworksProject2 C)

set(CMAKE_C_STANDARD 11)

include_directories(Project2)

add_executable(NetworksProject2
        Project2/project2.c
        Project2/project2.h
        Project2/student2.c)
