cmake_minimum_required(VERSION 3.0)

project("TicTacToe")

set(CMAKE_CXX_STANDARD 17)

file(GLOB SOURCES "src/*.cpp")

add_executable("TicTacToe" ${SOURCES})