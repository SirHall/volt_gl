cmake_minimum_required(VERSION 3.7)

add_library(volt_gl ${CMAKE_CURRENT_SOURCE_DIR}/src/glad.c)
target_include_directories(volt_gl PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include/)