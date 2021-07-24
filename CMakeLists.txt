cmake_minimum_required(VERSION 3.8)
project(demo1)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES wechat.cpp)
set(INCLUDE_DIRECTORIES ./)
include_directories(includes_folder)
add_executable(demo1 ${SOURCE_FILES})