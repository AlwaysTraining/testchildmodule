cmake_minimum_required(VERSION 3.10)

add_library(foo STATIC foo.c)

install(TARGETS foo LIBRARY DESTINATION lib)
