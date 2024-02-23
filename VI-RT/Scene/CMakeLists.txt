cmake_minimum_required(VERSION 3.25)

target_sources(VI-RT PUBLIC scene.cpp tinyobjloader/tiny_obj_loader.cc)

target_include_directories(VI-RT PUBLIC ${CMAKE_CURRENT_LIST_DIR} ${CMAKE_CURRENT_LIST_DIR}/tinyobjloader)

