cmake_minimum_required(VERSION 3.13)
project(BST)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(.idea)

add_executable(BST
        .idea/BST.iml
        .idea/encodings.xml
        .idea/misc.xml
        .idea/modules.xml
        .idea/workspace.xml
        BST312.h
        main.cpp
        test.txt)
