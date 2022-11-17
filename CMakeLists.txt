cmake_minimum_required(VERSION 3.15)
project(Folders)
set(CMAKE_CXX_STANDARD 14)

add_subdirectory(test)
# Create the library rotapro3 target here.
add_library(rotapro3 test/test.cpp)

# Create your executable target (with a different name).
add_executable(rotapro3_exe src/main.cpp)
add_executable(test_exe test/test.cpp)
