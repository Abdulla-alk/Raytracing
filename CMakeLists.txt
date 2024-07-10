cmake_minimum_required(VERSION 3.10)

# Set the project name and version
project(Raytracer VERSION 1.0)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable
add_executable(raytracer main.cc)

# Include directories for header files
include_directories(${PROJECT_SOURCE_DIR})

# Optionally, if you have other source files, add them like this
# add_executable(raytracer main.cc other_source_file.cc)

# You can also list header files explicitly if needed, but it's not necessary
# add_executable(raytracer main.cc vec3.h color.h)
