cmake_minimum_required(VERSION 3.1)
project(motion_planning)

aux_source_directory(${PROJECT_SOURCE_DIR}/src SOURCE_DIR)

add_executable(Astar_node ${SOURCE_DIR})
