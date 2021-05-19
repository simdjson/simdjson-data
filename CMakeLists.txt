cmake_minimum_required(VERSION 3.9)

project(simdjson-data VERSION 0.1.0  LANGUAGES NONE)

add_subdirectory(jsonchecker)
add_subdirectory(jsonexamples)


add_library(test-data INTERFACE)
target_link_libraries(test-data INTERFACE jsonchecker-data jsonchecker-minefield-data jsonexamples-data)