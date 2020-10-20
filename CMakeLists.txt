cmake_minimum_required(VERSION 3.17)
project(practice_c C)

set(CMAKE_C_STANDARD 99)

add_executable(practice_c main.c src/Practice.c include/MemoryPool.h)