cmake_minimum_required (VERSION 2.6)
project(fhyGameServer)

include_directories("${PROJECT_SOURCE_DIR}/3rdparty/boost_1_64_0")

add_subdirectory(3rdparty)

add_executable(asiotest test/asiotest.cpp)