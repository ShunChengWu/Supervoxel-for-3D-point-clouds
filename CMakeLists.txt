cmake_minimum_required(VERSION 3.11)

project(FOO_PROJECT CXX)

add_executable(exe main.cc)

set_property(TARGET exe PROPERTY CXX_STANDARD 11)