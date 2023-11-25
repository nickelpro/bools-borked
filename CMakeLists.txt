cmake_minimum_required(VERSION 3.21)

project(bools-borked LANGUAGES C)

add_executable(bools-borked bools-borked.c)
target_compile_features(bools-borked PRIVATE c_std_23)
