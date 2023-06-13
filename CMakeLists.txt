cmake_minimum_required(VERSION 3.25)
project(calc_debugging)

set(CMAKE_CXX_STANDARD 17)

add_executable(calc_debugging calc.cpp lexer.cpp parser.cpp op.cpp)
