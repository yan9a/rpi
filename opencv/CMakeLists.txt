cmake_minimum_required(VERSION 2.8)
project( disp )
find_package( OpenCV REQUIRED )
add_executable( disp disp.cpp )
target_link_libraries( disp ${OpenCV_LIBS} )
