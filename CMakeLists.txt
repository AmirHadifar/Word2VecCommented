cmake_minimum_required(VERSION 3.6)
project(word2vec)

set(CMAKE_C_STANDARD 11)

set(SOURCE_FILES main.c)
add_executable(word2vec ${SOURCE_FILES})