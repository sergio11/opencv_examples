cmake_minimum_required(VERSION 2.8)
project( flann_matcher )
find_package( OpenCV REQUIRED )
add_executable( flann_matcher flann_matcher.cpp )
target_link_libraries( flann_matcher ${OpenCV_LIBS} )