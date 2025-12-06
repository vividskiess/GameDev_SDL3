# Set the minimum version of CMake required
cmake_minimum_required(VERSION 3.23)

# Define the project
project(
        GameDev_SDL3
        VERSION 1.0
        DESCRIPTION "My first SDL3 Game"
        LANGUAGES CXX
)

# Set the C++ standard to C++26
set(CMAKE_CXX_STANDARD 26)
set(CMAKE_CXX_STANDARD_REQUIRED ON)