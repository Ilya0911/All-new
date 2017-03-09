cmake_minimum_required(VERSION 3.6)
project(lr2)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_EXE_LINKERS_FLAGS -static)
set(SOURCE_FILES main.cpp)
add_executable(lr2 ${SOURCE_FILES})