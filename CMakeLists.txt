cmake_minimum_required (VERSION 3.15)

add_library(HTTPRequest include/HTTPRequest.hpp)
set_target_properties(HTTPRequest PROPERTIES LINKER_LANGUAGE CXX)
target_include_directories(HTTPRequest PUBLIC include)
