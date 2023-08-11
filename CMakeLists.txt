cmake_minimum_required(VERSION 3.10)
Project(effective_route_planning)

set(CMAKE_EXPORT_COMPILE_COMMANDS TRUE)
set(CMAKE_CXX_STANDARD 14)

include_directories(include)

add_library(effective_route_planning
    SHARED
    src/RoadNetwork.cpp)
