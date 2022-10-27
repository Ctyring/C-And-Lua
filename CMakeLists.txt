cmake_minimum_required(VERSION 3.0)
project(HelloWorld LANGUAGES C)


add_executable(HelloWorld main.c)

target_link_libraries(HelloWorld liblua.a m dl)

