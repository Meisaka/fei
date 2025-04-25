cmake_minimum_required(VERSION 3.24)
project(FeiScript)


add_executable(fei main.cpp compiler.cpp)
target_compile_features(fei PUBLIC cxx_std_20)

