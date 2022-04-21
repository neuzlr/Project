cmake_minimum_required(VERSION 3.0)

project(TEST)

# include_directories(include)

set(CMAKE_CXX_FLAGS "${CAMKE_CXX_FLAGS} -pthread")

add_compile_options(-g -Wall)

add_executable(server server.cpp)
add_executable(client client.cpp)

