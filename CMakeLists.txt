cmake_minimum_required(VERSION 3.20)

project(AutomatedOverlayTKA LANGUAGES CXX)

add_executable(AutomatedOverlayTKA main.cpp)
target_compile_features(AutomatedOverlayTKA PRIVATE cxx_std_17)
set_target_properties(AutomatedOverlayTKA PROPERTIES CXX_EXTENSIONS OFF)
