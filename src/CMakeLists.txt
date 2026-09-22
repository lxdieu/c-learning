cmake_minimum_required(VERSION 4.4.1)

project(cpp_learning LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(cpp-learning
    helloworld/main.cpp
)