cmake_minimum_required(VERSION 3.22.3)

project(main)

# get the headers
include_directories(include)

# apparently this is bad but whatever
file(GLOB SOURCES "src/*.cpp")

add_executable(${PROJECT_NAME} ${SOURCES})