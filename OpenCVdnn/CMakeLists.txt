cmake_minimum_required(VERSION 2.8)
project(objectDetection CXX)

include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
conan_basic_setup()

add_executable(objectDetection objectDetection.cpp)

set(CMAKE_BUILD_TYPE Debug)

target_link_libraries(objectDetection ${CONAN_LIBS})
