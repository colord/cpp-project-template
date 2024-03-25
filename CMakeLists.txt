cmake_minimum_required(VERSION 3.18)

project(Main LANGUAGES CXX)
set(TARGET main)
set(CMAKE_CXX_STANDARD 17)

# add src files here
add_executable(${TARGET}
  src/main.cpp
  src/add.cpp)

add_compile_options(-Wall -Wextra -Wpedantic -Wshadow -Wconversion -Wfloat-equal -Wnull-dereference -Wno-unused-parameter -O2 -fdiagnostics-color=always)

target_include_directories(${TARGET} PRIVATE include/)