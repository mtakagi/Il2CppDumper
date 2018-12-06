# Cmake version
cmake_minimum_required(VERSION 3.11)

# This roject use C++
project(Il2CppDumper CXX)
# Also C++11
set (CMAKE_CXX_STANDARD 11)

add_executable(il2cppdumper elf_utils.cpp il2cpp_utils.cpp Il2CppDumper.cpp)
