cmake_minimum_required(VERSION 3.12)

project(cognitive-cpp)

include( ${CMAKE_SOURCE_DIR}/cmake/bootstrap.cmake )

add_subdirectory(lynx)
add_subdirectory(vesta)
