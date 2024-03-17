cmake_minimum_required(VERSION 3.27)
project(cpp_labs)

set(CMAKE_CXX_STANDARD 17)

add_executable(cpp_labs main.cpp)
add_executable(1-1 1-1.cpp
        6/Program.cpp)
add_executable(1-2 1-2.cpp)
add_executable(1-3 1-3.cpp)
add_executable(2 2.cpp)
add_executable(3-minmax 3-minmax.cpp)
add_executable(3-bubble 3-bubble.cpp)
add_executable(3-quick 3-quick.cpp)
add_executable(4-func.cpp 4.cpp)
add_executable(5 5.cpp)
add_executable(5-encrypt 5-encrypt.cpp)
add_executable(6 6/Program.cpp 6/StringM.cpp 6/StringM.h 4-func.cpp 4-func.h)
add_executable(8 8/8.cpp 6/StringM.h 6/StringM.cpp 4-func.h 4-func.cpp)
add_executable(8-encrypt 8/8-encrypt.cpp)
add_executable(9-1 9/9-1.cpp
        9/9-1.h)
add_executable(10 10/10.cpp 10/LinkedList.h 10/LinkedList.cpp)
add_executable(7 7.cpp)
