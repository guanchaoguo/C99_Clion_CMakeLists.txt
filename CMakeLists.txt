cmake_minimum_required(VERSION 3.10)

project(HelloProject C)

include_directories(hello)

add_executable(main main.c hello/hello.c)
