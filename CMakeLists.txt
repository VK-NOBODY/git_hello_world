cmake_minimum_required(VERSION 3.28)
project(git_hello_world)

set(CMAKE_CXX_STANDARD 17)

add_executable(git_hello_world main.cpp
        useful_header_file.h)
