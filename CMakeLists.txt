# 指定 CMake 的最低版本要求
cmake_minimum_required(VERSION 2.8)

# 设置项目名称
project(IPv6_VPN_First)

# 设置 C++ 标准
set(CMAKE_CXX_STANDARD 11)
set(EXECUTABLE_OUTPUT_PATH ../bin)
# 添加可执行文件
add_executable(IPv6_VPN_First hello.cpp)

