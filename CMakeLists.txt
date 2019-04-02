cmake_minimum_required(VERSION 3.13)
project(GPS_SIM_SDR_1_0 C)

set(CMAKE_C_STANDARD 99)

add_executable(GPS_SIM_SDR_1_0 gpssim.c)

TARGET_LINK_LIBRARIES(GPS_SIM_SDR_1_0 libm.so)

#test