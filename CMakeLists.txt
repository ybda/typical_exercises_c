cmake_minimum_required(VERSION 3.26)
project(cexercises C)

set(CMAKE_C_STANDARD 11)

add_executable(${PROJECT_NAME} src/main.c
        src/math.h
        src/hexToDec.h
        src/hexToDec.c
        src/strutil.h
        src/romanNumParser.c
        src/romanNumParser.h)
