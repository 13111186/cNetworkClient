cmake_minimum_required(VERSION 3.8)
project(cNetworkClient)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES client.c)
add_executable(cNetworkClient ${SOURCE_FILES})