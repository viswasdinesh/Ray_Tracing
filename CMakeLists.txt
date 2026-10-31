cmake_minimum_required ( VERSION 3.1.0...4.0.0 )

project ( Ray_Tracing LANGUAGES CXX )

# Set to C++11
set ( CMAKE_CXX_STANDARD          11 )
set ( CMAKE_CXX_STANDARD_REQUIRED ON )
set ( CMAKE_CXX_EXTENSIONS        OFF )

include_directories(src)
include_directories(include)
add_executable(ppm src/main.cc)