cmake_minimum_required(VERSION 3.17.2)
project(HelloCuda
    VERSION 0.1.0
    DESCRIPTION "Learning CUDA"
    LANGUAGES CXX CUDA)

# Project wide C++ standard
set(CMAKE_CXX_STANDARD 17)
 
add_subdirectory(src)
