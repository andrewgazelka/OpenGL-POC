
add_executable(cube3d Cube3D.cpp)
target_link_libraries(cube3d glm glad ${SDL2_LIBRARIES})
include_directories(cube3d ${SDL2_INCLUDE_DIRS})
