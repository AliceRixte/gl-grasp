
cmake_minimum_required(VERSION 3.11-3.18)


project(graspgl)

add_library(graspgl src/graspgl.cpp)

target_include_directories(${PROJECT_NAME}
    PUBLIC ${PROJECT_SOURCE_DIR}/include)

target_compile_features(graspgl PUBLIC cxx_std_20)