add_executable(cube-lit1-vbo CubeLit1VBO.cpp)

target_link_libraries(cube-lit1-vbo glm glad ${SDL2_LIBRARIES})
include_directories(cube-lit1-vbo ${SDL2_INCLUDE_DIRS})
