cmake_minimum_required(VERSION 3.1)
project(TravisCITest)

# Write demo-config.h
message("Check if we can get messages out?")

add_executable(travisDemo main.cpp)
