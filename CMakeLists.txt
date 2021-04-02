cmake_minimum_required(VERSION 3.17)
project(hw04)

set(CMAKE_CXX_STANDARD 14)

find_package(SDL2 REQUIRED)

include_directories(${SDL2_INCLUDE_DIRS})

include_directories(lib/glad)
include_directories(lib/glm)
include_directories(lib/glm/detail)
include_directories(lib/glm/ext)
include_directories(lib/glm/gtc)
include_directories(lib/glm/gtx)
include_directories(lib/glm/simd)

add_subdirectory(triangle-colored)
add_subdirectory(model-load)
add_subdirectory(cube-lit1-vbo)
add_subdirectory(cube-lit)
add_subdirectory(cube3d)

add_subdirectory(lib/glad)
add_subdirectory(lib/glm)

