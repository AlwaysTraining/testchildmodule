cmake_minimum_required(VERSION 3.10)

add_library(foo SHARED foo.c)

install(TARGETS foo LIBRARY DESTINATION ${CMAKE_INSTALL_PREFIX}/lib)
