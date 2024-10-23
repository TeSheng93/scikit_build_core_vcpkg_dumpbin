cmake_minimum_required(VERSION 3.30.0)

project("dumpbin_not_found" 
    VERSION 0.0.0  
    LANGUAGES C CXX
)

add_library(lib_1
    SHARED
    lib_1.cpp
)


install(TARGETS lib_1
    RUNTIME DESTINATION lib_1
)