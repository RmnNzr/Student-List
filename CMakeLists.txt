cmake_minimum_required(VERSION 3.5)
project(Student_List)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Student_List
        src/List.h
        src/main.cpp
        src/Student.cpp
        src/Student.h
        src/Node.h 
	src/StudentList.cpp 
	src/StudentList.h)
