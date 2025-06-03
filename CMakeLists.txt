cmake_minimum_required(VERSION 3.31)
project(Lab13)

set(CMAKE_CXX_STANDARD 20)

add_executable(Lab13 main.cpp
exp.cpp
parser.cpp
scanner.cpp
token.cpp
visitor.cpp)
