cmake_minimum_required(VERSION 3.19)
project(VkEngine VERSION 1.0.0)

find_package(Vulkan REQUIRED FATAL_ERROR)

add_subdirectory(external)
add_subdirectory(src)
