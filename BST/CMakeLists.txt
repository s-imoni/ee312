cmake_minimum_required(VERSION 3.15)
project(BST)

set(CMAKE_CXX_STANDARD 11)

include_directories(.)

add_executable(BST
        BST312.h
        main.cpp
        test.txt)
