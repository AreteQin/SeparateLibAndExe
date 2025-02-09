cmake_minimum_required(VERSION 3.8)
project(test_executable)

add_executable(my_exe main.cpp)
target_include_directories(my_exe PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../Library)
target_link_libraries(my_exe ${CMAKE_CURRENT_SOURCE_DIR}/../Library/lib/libmy_lib.a)