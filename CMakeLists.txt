cmake_minimum_required(VERSION 3.10)

# Set the project name
project(Raytracer)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable
add_executable(raytracer main.cc)
