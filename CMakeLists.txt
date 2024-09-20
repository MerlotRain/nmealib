cmake_minimum_required(VERSION 3.10)
project(nmealib)

add_library(nmealib STATIC
    src/context.c
    src/generate.c
    src/generator.c
    src/gmath.c
    src/info.c
    src/parse.c
    src/parser.c
    src/sentence.c
    src/time.c
    src/tok.c
    src/util.c   
)

target_include_directories(nmealib PUBLIC ${CMAKE_CURRENT_LIST_DIR}/include)

