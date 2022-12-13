cmake_minimum_required(VERSION 3.24)
project(tinyrenderer)

set(CMAKE_CXX_STANDARD 17)

add_executable(tinyrenderer main.cpp lib/tinyrenderer.h)
