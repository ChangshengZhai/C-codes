cmake_minimum_required(VERSION 3.16)
project(2020os C)

set(CMAKE_C_STANDARD 99)

add_executable(2020os  eat_think.c)
find_package(Threads REQUIRED)
target_link_libraries(2020os Threads::Threads)