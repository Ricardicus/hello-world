# CMakeLists.txt

cmake_minimum_required(VERSION 3.10)

# set the project name and version
project(HelloWorld VERSION 1.0)

# specify the C++ standard
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# add the executable
add_executable(HelloWorld main.cpp)

install(TARGETS HelloWorld DESTINATION /usr/bin)
