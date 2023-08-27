cmake_minimum_required(VERSION 3.22)

project(luna_installer LANGUAGES C CXX)

include_directories(include)

add_executable(luna_installer
    src/main.cpp
)