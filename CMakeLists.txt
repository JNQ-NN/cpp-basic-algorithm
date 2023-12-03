cmake_minimum_required(VERSION 3.0.0)
project(cpp-basic-algorithm VERSION 0.1.0 LANGUAGES C CXX)

include(CTest)
enable_testing()

add_executable(cpp-basic-algorithm main.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
