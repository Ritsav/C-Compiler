cmake_minimum_required(VERSION 3.30)
project(C_Compiler C)

set(CMAKE_C_STANDARD 99)

add_executable(C_Compiler
        main.c
        chunk.c
        debug.c
        memory.c
        value.c
)
