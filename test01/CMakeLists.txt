﻿# CMakeList.txt: test01 的 CMake 项目，在此处包括源代码并定义
# 项目特定的逻辑。
#
cmake_minimum_required (VERSION 3.8)
#CMake的版本

# 将源代码添加到此项目的可执行文件。
add_executable (test01 "test01.cpp" "test01.h")#实现编译的功能，.cpp和.h文件都是源文件

# TODO: 如有需要，请添加测试并安装目标。
