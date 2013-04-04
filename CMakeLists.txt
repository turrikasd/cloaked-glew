cmake_minimum_required (VERSION 2.6)
project (cloaked_glew)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_SOURCE_DIR}/bin)

include_directories("${PROJECT_SOURCE_DIR}/src")

add_subdirectory(src)
