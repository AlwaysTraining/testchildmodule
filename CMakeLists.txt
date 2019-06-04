add_library(foo STATIC foo.c)

install(TARGETS foo LIBRARY DESTINATION lib)
