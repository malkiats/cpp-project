cmake_minimum_required(VERSION 3.10)

# Project Name and Version
project(CppProject VERSION 1.0)

# Set C++ Standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable
enable_testing()
add_executable(my_cpp_app src/main.cpp)
add_test(NAME RunApp COMMAND my_cpp_app)