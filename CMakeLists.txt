cmake_minimum_required(VERSION 3.8)

add_subdirectory(subprojects/qt5/qtbase)

project(qt-cmake-example LANGUAGES CXX)

file(GLOB SRC src/*.cpp)
