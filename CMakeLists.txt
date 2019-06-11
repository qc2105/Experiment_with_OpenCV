cmake_minimum_required(VERSION 3.1.0)
project("findKnownObject")

find_package(OpenCV REQUIRED)

add_executable(fko findKnownObject.cpp)
target_link_libraries(fko ${OpenCV_LIBS})