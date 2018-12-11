cmake_minimum_required(VERSION 3.9)
project(mybase)

set(CMAKE_CXX_STANDARD 11)

#指定生成的版本
set(CMAKE_BUILD_TYPE RELEASE)
#set(CMAKE_BUILD_TYPE DEBUG)


add_executable(mybase main.cpp)