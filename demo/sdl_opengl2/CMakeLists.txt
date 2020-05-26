cmake_minimum_required(VERSION 2.8.9)
project(gg LANGUAGES C)
set(CMAKE_C_STANDARD 99)

add_executable(gg main.c )

target_link_libraries(gg SDL2 GL m)
