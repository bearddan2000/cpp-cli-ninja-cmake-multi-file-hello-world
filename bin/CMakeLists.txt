list(APPEND SRC "greeting.cpp" "greeting.h" "main.cpp")

cmake_minimum_required(VERSION 3.27.3)
project(main)
add_executable(main ${SRC})