cmake_minimum_required (VERSION 3.0)

project (foo)

add_library( foo
src/foo.c
)

INSTALL( TARGETS foo DESTINATION "lib")
INSTALL( FILES src/foo.h DESTINATION "include")


