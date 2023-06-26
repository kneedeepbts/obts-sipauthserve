cmake_minimum_required(VERSION 3.20)
project(obts_sipauthserve)

set(CMAKE_CXX_STANDARD 20)

include_directories(include)

add_subdirectory(apps)
add_subdirectory(fixmes)

add_executable(obts_sipauthserve apps/sipauthserve.cpp)
