cmake_minimum_required(VERSION 3.16)
project(helloworld)

set(CMAKE_CXX_STANDARD 14)

add_executable(helloworld main.cpp)

install(TARGETS helloworld DESTINATION bin)
