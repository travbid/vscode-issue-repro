cmake_minimum_required(VERSION 3.20)

project(cppsample)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_compile_options(-stdlib=libc++)
add_link_options(-stdlib=libc++)

add_executable(main main.cpp)
