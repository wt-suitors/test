cmake_minimum_required(VERSION 3.0.0)
project(Use_Eigen3 VERSION 0.1.0)

include(CTest)
enable_testing()

add_executable(Use_Eigen3 main.cpp)
include_directories("/usr/locate/include/eigen3")

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
