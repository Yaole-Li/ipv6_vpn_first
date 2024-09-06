cmake_minimum_required(VERSION 3.10)

# 项目名称
project(IPv6_VPN_First)

# 指定C++标准
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# 指定可执行文件输出地址
set(EXECUTABLE_OUTPUT_PATH ../bin)

# 添加源文件
add_executable(IPv6_VPN_First
    main.cpp
)
