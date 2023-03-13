cmake_minimum_required(VERSION 3.10)  # 指定 CMake 的最低版本要求

project(hello-world)  # 指定项目名称

# 添加可执行文件
add_executable(hello main.cpp hello.cpp)
