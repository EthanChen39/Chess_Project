cmake_minimum_required(VERSION 3.17)
project(Chess)

set(CMAKE_CXX_STANDARD 14)

add_executable(Chess Board.cpp Board.h Player.cpp Player.h Piece.cpp Piece.h)