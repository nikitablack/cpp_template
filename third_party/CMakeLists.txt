cmake_minimum_required(VERSION 3.25 FATAL_ERROR)

add_subdirectory(fmt SYSTEM)

if(BUILD_TESTS)
    add_subdirectory(catch SYSTEM)
endif()
