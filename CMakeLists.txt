cmake_minimum_required(VERSION 3.10.0)
project(Sentinel VERSION 0.1.0 LANGUAGES C CXX)

add_executable(Sentinel main.cpp src/sniffer.cpp)
target_link_libraries(Sentinel pcap)

include(CTest)
enable_testing()

