add_executable(triangle-colored TriangleColored.cpp)

target_link_libraries(triangle-colored glm glad ${SDL2_LIBRARIES})
include_directories(triangle-colored ${SDL2_INCLUDE_DIRS})
