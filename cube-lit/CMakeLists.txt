add_executable(cube-lit CubeLit.cpp)


target_link_libraries(cube-lit glm glad ${SDL2_LIBRARIES})
include_directories(cube-lit ${SDL2_INCLUDE_DIRS})
