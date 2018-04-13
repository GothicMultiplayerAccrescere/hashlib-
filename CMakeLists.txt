cmake_minimum_required(VERSION 3.3)
project(Hashlib2p)

file(GLOB_RECURSE SRC
    src/*.cpp
    src/*.h
)

add_library(hashlib STATIC ${SRC})
