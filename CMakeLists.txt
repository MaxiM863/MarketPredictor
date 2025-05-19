cmake_minimum_required(VERSION 3.31)

project(Market)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(Market market.cpp)

target_sources(Market PRIVATE 
"hmm.cpp")