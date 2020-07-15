cmake_minimum_required(VERSION 3.15)
project(cJSON)

set(CMAKE_C_STANDARD 99)

add_executable(json src/cJSON.h src/cJSON.c src/test.c)