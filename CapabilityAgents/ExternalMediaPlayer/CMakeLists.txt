cmake_minimum_required(VERSION 3.1 FATAL_ERROR)
project(ExternalMediaPlayer LANGUAGES CXX)

include(${AVS_CORE}/build/BuildDefaults.cmake)

add_subdirectory("src")
add_subdirectory("test")
