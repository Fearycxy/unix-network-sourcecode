cmake_minimum_required(VERSION 3.8)
project(unpv13e)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        config.h
        lib/unp.h
        tcpcliserv/tcpserv01.c
        lib/error.c
        lib/wrapsock.c
        lib/str_echo.c
        lib/wrapunix.c
        lib/wrapstdio.c
        lib/readn.c
        lib/writen.c)

add_executable(unpv13e ${SOURCE_FILES})
