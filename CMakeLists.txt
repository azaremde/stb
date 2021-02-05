cmake_minimum_required(VERSION 3.16)

project(stb_image)

add_library(stb_image STATIC src/stb_image.cpp)

target_include_directories(stb_image PUBLIC ${CMAKE_SOURCE_DIR}/include)