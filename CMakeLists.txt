cmake_minimum_required(VERSION 3.15 FATAL_ERROR)
project(test LANGUAGES CXX)
add_executable(main test.cpp output.cpp output.h)