# Author: Kynan Justis
# Date: Sep 7 2017

cmake_minimum_required(VERSION 3.9)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD)

# create project
project(ip-testing)

# find packages
find_package(OpenCV REQUIRED)

# add sub dir
add_subdirectory(src)
