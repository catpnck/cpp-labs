cmake_minimum_required(VERSION 3.27)
project(cpp_labs)

set(CMAKE_CXX_STANDARD 17)

add_executable(cpp_labs main.cpp)
add_executable(1-1 lab1/1-1.cpp
        lab6/Program.cpp)
add_executable(1-2 lab1/1-2.cpp)
add_executable(1-3 lab1/1-3.cpp)
add_executable(2 lab2/2.cpp)
add_executable(3-minmax lab3/3-minmax.cpp)
add_executable(3-bubble lab3/3-bubble.cpp)
add_executable(3-quick lab3/3-quick.cpp)
add_executable(lab4/4-func.cpp lab4/4.cpp)
add_executable(5 5.cpp)
add_executable(5-encrypt 5-encrypt.cpp)
add_executable(lab6 lab6/Program.cpp lab6/StringM.cpp lab6/StringM.h lab4/4-func.cpp lab4/4-func.h)
add_executable(lab8 lab8/8.cpp lab6/StringM.h lab6/StringM.cpp lab4/4-func.h lab4/4-func.cpp)
add_executable(8-encrypt lab8/8-encrypt.cpp)
add_executable(9-1 lab9/9-1.cpp
        lab9/9-1.h)
add_executable(lab10 lab10/10.cpp lab10/LinkedList.h lab10/LinkedList.cpp)
add_executable(7 7.cpp)
