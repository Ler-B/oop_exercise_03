cmake_minimum_required(VERSION 3.17)
project(oop_exercise_03)

set(CMAKE_CXX_STANDARD 14)

add_executable(oop_exercise_03 main.cpp figure.hpp figure.cpp triangle.hpp triangle.cpp octagon.cpp octagon.hpp hexagon.cpp hexagon.hpp)