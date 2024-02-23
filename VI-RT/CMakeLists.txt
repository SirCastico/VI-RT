cmake_minimum_required(VERSION 3.25)


add_executable(VI-RT main.cpp)

add_subdirectory(3DSortingStruct)
add_subdirectory(Camera)
add_subdirectory(Image)
add_subdirectory(Light)
add_subdirectory(Primitive)
add_subdirectory(Rays)
add_subdirectory(Renderer)
add_subdirectory(Scene)
add_subdirectory(Shader)
add_subdirectory(utils)


#target_link_libraries(VI-RT PUBLIC tinyobjloader)