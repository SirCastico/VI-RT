cmake_minimum_required(VERSION 3.25)


add_subdirectory(Geometry)
add_subdirectory(BRDF)

target_sources(VI-RT PUBLIC BB.hpp primitive.hpp)

target_include_directories(VI-RT PUBLIC ${CMAKE_CURRENT_LIST_DIR})
