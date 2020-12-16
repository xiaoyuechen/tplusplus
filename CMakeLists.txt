cmake_minimum_required(VERSION 3.14)

project(tplusplus LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

cmake_policy(SET CMP0077 NEW)

add_library(tplusplus INTERFACE)
target_include_directories(tplusplus INTERFACE "include")
