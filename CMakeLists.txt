cmake_minimum_required(VERSION 3.27)
project(FinalCompiler)

set(CMAKE_CXX_STANDARD 17)

add_executable(FinalCompiler main.cpp
        SyntaxAnalyzer.h
        SyntaxAnalyzer.cpp
        LexAnalyzer.h
        LexAnalyzer.cpp
        LexAnalyzer.cpp)
