cmake_minimum_required(VERSION 3.20)

project(cpp_software_rasterizer LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(rasterizer main.cpp)
