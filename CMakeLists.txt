# CMakeList.txt : CMake project for Employee Manager, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("Employee Manager")

# Add source to this project's executable.
add_executable (CMakeTarget "Employee Manager.cpp" "Employee Manager.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET CMakeTarget PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
