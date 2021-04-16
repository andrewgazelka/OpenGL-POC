add_executable(blankscreen BlankScreenSDL.cpp)
target_link_libraries(blankscreen glm glad ${SDL2_LIBRARIES})
include_directories(blankscreen ${SDL2_INCLUDE_DIRS})
