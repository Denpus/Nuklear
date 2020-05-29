cmake_minimum_required(VERSION 2.8.9)
project(nuklear-demo LANGUAGES C)
set(CMAKE_C_STANDARD 99)

add_executable(opengles2 sdl_opengles2/main.c )

target_link_libraries(opengles2 SDL2 GL m)
