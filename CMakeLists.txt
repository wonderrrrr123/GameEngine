cmake_minimum_required(VERSION 3.14..3.30)

project(
    GAMEENGINE
    LANGUAGES CXX C
)

add_executable(main src/main.cpp)
set_target_properties(main PROPERTIES CXX_STANDARD 20)
