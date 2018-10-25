cmake_minimum_required(VERSION 3.12)
project(memcached_1_5_11 C)

set(CMAKE_C_STANDARD 11)
set(BUILD_DIR .)

include_directories(.)
add_custom_target(demo COMMAND make -C ${BUILD_DIR})
