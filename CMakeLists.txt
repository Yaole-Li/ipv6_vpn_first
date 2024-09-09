cmake_minimum_required(VERSION 2.0)

# 设置项目名称
project(ipv6_vpn_first)

# 设置 C++ 标准
set(CMAKE_CXX_STANDARD 11)

# 添加可执行文件
set(EXECUTABLE_OUTPUT_PATH ../bin)
add_executable(ipv6_vpn_first main.cpp)
