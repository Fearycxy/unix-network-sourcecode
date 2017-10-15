cmake_minimum_required(VERSION 3.8)
project(intro)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        daytimetcpcli.c
        ../lib/unp.h
        ../config.h
        )
set()

add_executable(intro ${SOURCE_FILES})