cmake_minimum_required(VERSION 3.1)
project(503_SeamsSingsRounding)

add_executable(${PROJECT_NAME}_bin main.cpp)
target_link_libraries(${PROJECT_NAME}_bin igl::core igl::opengl_glfw tutorials)
