cmake_minimum_required(VERSION 3.25)


target_sources(VI-RT PUBLIC triangle.cpp mesh.cpp )

target_include_directories(VI-RT PUBLIC ${CMAKE_CURRENT_LIST_DIR})

