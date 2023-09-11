cmake_minimum_required(VERSION 3.5 FATAL_ERROR)

find_package(PkgConfig REQUIRED)

project(blescan)

add_executable(blescan
    scanner.c
)

target_link_libraries(blescan
	bluetooth
)
