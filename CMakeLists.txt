cmake_minimum_required(VERSION 3.25)
project(find_digits)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)
include_directories(test-unit)

add_executable(find_digits
        src/find_digits.h
        test-unit/catch.hpp
        test-unit/test.cpp)
