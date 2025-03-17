cmake_minimum_required(VERSION 3.30)
project(test C)

set(CMAKE_C_STANDARD 11)

include_directories(.)
include_directories(Code)
include_directories(Funcion)

add_executable(test Code/Main.c)
add_executable(test2 Funcion/Gauss.c)
