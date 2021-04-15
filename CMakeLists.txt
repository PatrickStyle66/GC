# cmake_minimum_required(VERSION <specify CMake version here>)
project(GC C)

set(CMAKE_C_STANDARD 99)

add_executable(GC Pyramid.c)

target_link_libraries(GC -lOpenGL32 -lfreeGLUT -lglu32)