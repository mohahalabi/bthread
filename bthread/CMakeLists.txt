cmake_minimum_required(VERSION 3.12.2)
project(bthread C)

set(CMAKE_C_STANDARD 99)

add_executable(bthread main.c sources/BThreadLib.c headers/BThreadLib.h)