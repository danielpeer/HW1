cmake_minimum_required(VERSION 3.10)
project(HW1 C)

set(CMAKE_C_STANDARD 90)
set(GCC_COVERAGE_COMPILE_FLAGS "-c -fmessage-length=0 –ansi -Wall -O3 -Wextra -Werror -pedantic-errors")
add_executable(hw1 main.c Parser.c Parser.h List.c List.h)