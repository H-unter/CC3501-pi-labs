cmake_minimum_required(VERSION 3.12)
project(SocketsDemo)
set(CMAKE_CXX_STANDARD 20)
set(COMPILE_DEFINITIONS -O2 -Wall)
add_executable(http_client src/http_client.cpp)
target_link_libraries(http_client curl)
