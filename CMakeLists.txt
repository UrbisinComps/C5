cmake_minimum_required(VERSION 4.0)
project(C5)

set(CMAKE_CXX_STANDARD 20)

add_executable(C5 main.cpp token.h token.cpp ast.h ast.cpp scanner.h scanner.cpp visitor.h visitor.cpp parser.h parser.cpp)