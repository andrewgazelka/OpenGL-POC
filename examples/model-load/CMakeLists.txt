add_executable(model-load ModelLoad.cpp)

target_link_libraries(model-load glm glad ${SDL2_LIBRARIES})
include_directories(model-load ${SDL2_INCLUDE_DIRS})
