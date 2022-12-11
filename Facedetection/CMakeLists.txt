cmake_minimum_required(VERSION 2.8)
project(Facedetection CXX)


include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
conan_basic_setup()

add_executable(Facedetection facedetect.cpp)

target_link_libraries(Facedetection ${CONAN_LIBS})
