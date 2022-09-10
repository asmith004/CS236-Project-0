cmake_minimum_required(VERSION 3.16)
project(CS236_Project_0)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(CS236_Project_0
        Book.cpp
        Book.h
        BookCreator.cpp
        BookCreator.h
        BookListCreator.cpp
        BookListCreator.h
        Info.cpp
        Info.h
        Library.cpp
        Library.h
        main.cpp)

file(COPY Lab0PassOffCases DESTINATION ${CMAKE_BINARY_DIR})